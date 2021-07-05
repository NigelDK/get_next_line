# get_next_line
Validated on 23-10-2020.

May it be a file, stdin, or a network connection, I will always need a way to read content line by line. This function does exactly that.

- Prototype: int get_next_line(int fd, char **line);
- Parameters:	#1. file descriptor for reading
				#2. the value of what has been read
- Return value:	1	a line has been read
				0	EOF has been reached
				-1	an error occured