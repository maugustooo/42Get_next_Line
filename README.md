# Get_Next_Line
This function returns a line that can be read from a file descriptor

<div align="center">
	<h1><a href="https://github.com/maugustooo/42Get_next_line/blob/main/en.subject.pdf">Subject</a></h1>
</div>

### Functions from existing libraries

Function | Format | Description | Library
--- | --- | --- | ---
read | `ssize_t	read(int fd, void *buff, size_t count)` | Reads "count" bytes in "buff", contained in fd. Returns number of bytes read | `unistd.h`
open | `int	open(const char *pathname, int flags, mode_t mode)` | Opens file contained in "pathname". The variable "flags" define mode of opening. The variable "mode" is optional, and defines permission in creating new file. Returns file descriptor. | `fcntl.h`
close | `int	close(int fd)` | Closes file open in fd. Returns 0. | `fcntl.h`
