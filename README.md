ptxt: Fast Text-to-PDF Converter
================================

The *ptxt* utility is a text-to-PDF converter aiming to:

- fast
- low memory consumption
- stream converting, line by line
- light weight

To reach these goals, *ptxt* uses an ad-hoc solution instead of depending on a full-feature PDF library or rendering engine.

Output Style
------------

Outputs are in the style of line printers:

- 80 columns
- 66 lines
- *Courier* font

The page size is set to A4 with proper margins.

Usage
-----

- `ptxt file`

	Convert *file* to PDF.
	The result is printed to the standard output.
	If *file* is omitted, the standard input is used.

- `ptxt --help`

	Print the usage.

- `ptxt --version`

	Print version information.

Installation
------------

	$ make
	$ sudo make install
