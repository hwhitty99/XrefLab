# XrefLab
`xref` Prints a list of C identifiers in a source code file using the xref command `xref [your_filename]`.
Sorts the list of identifiers into ascending order.
For each identifier, lists the line numbers on which it occurs.
Does not print C reserved words; only user defined identifiers.

`xref2` accepts optional positional command line arguments for input and output file names.
If no file names are provided, it will read from stdin and write to stdout.
If one file name is provided, it will read from it and write to stdout.
If two file names are provided, it will read from the first file name, and write to the second file name.

`xref3` accepts optional keyword command line arguments for input and output file names. `-i` will be used as the input file and `-o` will be used as the output file.
Reasonably handles bad input such as `xref3 -i, xref3 -o, xref3 in.c, xref3 -i -o.`
