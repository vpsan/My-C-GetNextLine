# DESCRIPTION

get_next_line() reads line from a file descriptor
with defined buffer size (default 4096). Supports multiple files.

RETURN VALUES: 1 <=> A line has been read; 0 <=> EOF has been reached; -1 <=> An ERROR happend

# Prototype:

int get_next_line(int fd, char **line)
