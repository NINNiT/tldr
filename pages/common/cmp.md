# cmp

> Compare two files byte by byte.
> More information: <https://www.gnu.org/software/diffutils/manual/html_node/Invoking-cmp.html>.

- Output char and line number of the first difference between two files:

`cmp {{path/to/file1}} {{path/to/file2}}`

- Output info of the first difference: char, line number, bytes, and values:

`cmp {{[-b|--print-bytes]}} {{path/to/file1}} {{path/to/file2}}`

- Output the byte numbers and values of every difference:

`cmp {{[-v|--verbose]}} {{path/to/file1}} {{path/to/file2}}`

- Compare files but output nothing, yield only the exit status:

`cmp {{[-s|--quiet]}} {{path/to/file1}} {{path/to/file2}}`
