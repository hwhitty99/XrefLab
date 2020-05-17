# comp_381_lab6

Prints a list of C identifiers in a source code file.

Xref2 accepts optional positional command line arguments for input and output file names.
If no file names are provided, read from stdin and write to stdout.
If one file name is provided, read from it and write to stdout.
If two file names are provided, read from the first file name, and write to the second file name.

Xref3 accepts optional keyword command line arguments for input and output file names.
Reasonably handles bad input such as xref3 -i, xref3 -o, xref3 in.c, xref3 -i -o.
