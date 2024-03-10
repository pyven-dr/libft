# Libft

## This project is about coding a C library. It will contain a lot of general purpose functions your programs will rely upon.

### Functions from `<ctype.h>`

- [`ft_isalpha`](src/ft_isalpha.c)	- checks  for  an  alphabetic  character.
- [`ft_isdigit`](src/ft_isdigit.c)	- checks for a digit (0 through 9).
- [`ft_isalnum`](src/ft_isalnum.c)	- checks for an alphanumeric character.
- [`ft_isascii`](src/ft_isascii.c)	- checks whether c fits into the ASCII character set.
- [`ft_isprint`](src/ft_isprint.c)	- checks for any printable character.
- [`ft_toupper`](src/ft_toupper.c)	- convert char to uppercase.
- [`ft_tolower`](src/ft_tolower.c)	- convert char to lowercase.

### Functions from `<string.h>`

- [`ft_memset`](src/ft_memset.c)	- fill memory with a constant byte.
- [`ft_strlen`](src/ft_strlen.c)	- calculate the length of a string.
- [`ft_bzero`](src/ft_bzero.c)	- zero a byte string.
- [`ft_memcpy`](src/ft_memcpy.c)	- copy memory area.
- [`ft_memmove`](src/ft_memmove.c)	- copy memory area.
- [`ft_strlcpy`](src/ft_strlcpy.c)	- copy string to an specific size.
- [`ft_strlcat`](src/ft_strlcat.c)	- concatenate string to an specific size.
- [`ft_strchr`](src/ft_strchr.c)	- locate character in string.
- [`ft_strrchr`](src/ft_strrchr.c)	- locate character in string.
- [`ft_strncmp`](src/ft_strncmp.c)	- compare two strings.
- [`ft_memchr`](src/ft_memchr.c)	- scan memory for a character.
- [`ft_memcmp`](src/ft_memcmp.c)	- compare memory areas.
- [`ft_strnstr`](src/ft_strnstr.c)	- locate a substring in a string.
- [`ft_strdup`](src/ft_strdup.c)	- creates a dupplicate for the string passed as parameter.

### Functions from `<stdlib.h>`
- [`ft_atoi`](src/ft_atoi.c)	- convert a string to an integer.
- [`ft_calloc`](src/ft_calloc.c)	- allocates memory and sets its bytes' values to 0.

### Non-standard functions
- [`ft_substr`](src/ft_substr.c)	- returns a substring from a string.
- [`ft_strjoin`](src/ft_strjoin.c)	- concatenates two strings.
- [`ft_strtrim`](src/ft_strtrim.c)	- trims the beginning and end of string with specific set of chars.
- [`ft_split`](src/ft_split.c)	- splits a string using a char as parameter.
- [`ft_itoa`](src/ft_itoa.c)	- converts a number into a string.
- [`ft_strmapi`](src/ft_strmapi.c)	- applies a function to each character of a string.
- [`ft_striteri`](src/ft_striteri.c)	- applies a function to each character of a string.
- [`ft_putchar_fd`](src/ft_putchar_fd.c)	- output a char to a file descriptor.
- [`ft_putstr_fd`](src/ft_putstr_fd.c)	- output a string to a file descriptor.
- [`ft_putendl_fd`](src/ft_putendl_fd.c)	- output a string to a file descriptor, followed by a new line.
- [`ft_putnbr_fd`](src/ft_putnbr_fd.c)	- output a number to a file descriptor.

### Linked list functions

- [`ft_lstnew`](src/ft_lstnew.c)	- creates a new list element.
- [`ft_lstadd_front`](src/ft_lstadd_front.c)	- adds an element at the beginning of a list.
- [`ft_lstsize`](src/ft_lstsize.c)	- counts the number of elements in a list.
- [`ft_lstlast`](src/ft_lstlast.c)	- returns the last element of the list.
- [`ft_lstadd_back`](src/ft_lstadd_back.c)	- adds an element at the end of a list.
- [`ft_lstclear`](src/ft_lstclear.c)	- deletes and free list.
- [`ft_lstiter`](src/ft_lstiter.c)	- applies a function to each element of a list.
- [`ft_lstmap`](src/ft_lstmap.c)	- applies a function to each element of a list.

### Vector functions

- [`new_vector`](src/new_vector.c) - create a new vector
- [`del_vector`](src/del_vector.c) - delete a vector
- [`get_elem_vector`](src/get_elem_vector.c) - return the element at the given index of the vector
- [`add_vector`](src/add_vector.c) - add an element to a vector

### Get_next_line

- [`get_next_line`](src/get_next_line.c) - read a file line by line from th project [get_next_line](https://github.com/pyven-dr/get_next_line)
