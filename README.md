# get_next_line
Get_next_line (42cursus) 2019-2020

## Status

- Status  : Completed
- Result  : 112%

### Compiling

Run the following commands:

* To compile
	- 'make'
* To remove objects:
	- 'make clean'
* To remove objects and binary file (program):
	- 'make fclean'
* To re-compile:
	- 'make re'

### Executing

To test the function, compile with main.c.

`gcc main.c src/get_next_line.c`

`./a.out tests/some_lines.txt`

If wanted to test with multiple file descriptors, compile with
main-multiple-fds.c

`gcc main-multiple-fds.c src/get_next_line.c`

`./a.out tests/some_lines.txt tests/nl_and_eof_one.txt`

[![forthebadge](https://forthebadge.com/images/badges/made-with-c.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

This is my solution for the get_next_line project from the School 42 programme,
For help, reach out to help:
mikuiper@student.codam.nl
