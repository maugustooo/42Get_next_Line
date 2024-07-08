# Get_Next_Line
This function returns a line that can be read from a file descriptor

## General notes

### Functions from existing libraries

Function | Format | Description | Library
--- | --- | --- | ---
read | `ssize_t	read(int fd, void *buff, size_t count)` | Reads "count" bytes in "buff", contained in fd. Returns number of bytes read | `unistd.h`
open | `int	open(const char *pathname, int flags, mode_t mode)` | Opens file contained in "pathname". The variable "flags" define mode of opening. The variable "mode" is optional, and defines permission in creating new file. Returns file descriptor. | `fcntl.h`
close | `int	close(int fd)` | Closes file open in fd. Returns 0. | `fcntl.h`

## Main Functions

### Libft functions

Function | Format
--- | ---
ft_strlen | `size_t	ft_strlen(const char *str)` 
ft_strchr | `char	*ft_strchr(const char *str, int c)` 
ft_strndup | `char	*ft_strndup(char *s1, int len)`
ft_strjoin | `char	*ft_strjoin(char *s1, char *s2)`
ft_strlentoc | `size_t	ft_strlentoc(char *s, char c)`
