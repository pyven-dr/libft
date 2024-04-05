# Libft

## Your very first own library

### This project is about coding a C library. It will contain a lot of general purpose functions your programs will rely upon.

### Functions from `<ctype.h>`

- [`ft_isalpha`](src/characters/ft_isalpha.c)	- checks  for  an  alphabetic  character.
- [`ft_isdigit`](src/characters/ft_isdigit.c)	- checks for a digit (0 through 9).
- [`ft_isalnum`](src/characters/ft_isalnum.c)	- checks for an alphanumeric character.
- [`ft_isascii`](src/characters/ft_isascii.c)	- checks whether c fits into the ASCII character set.
- [`ft_isprint`](src/characters/ft_isprint.c)	- checks for any printable character.
- [`ft_toupper`](src/characters/ft_toupper.c)	- convert char to uppercase.
- [`ft_tolower`](src/characters/ft_tolower.c)	- convert char to lowercase.

### Functions from `<string.h>`

- [`ft_memset`](src/memory/ft_memset.c)	- fill memory with a constant byte.
- [`ft_strlen`](src/string/ft_strlen.c)	- calculate the length of a string.
- [`ft_bzero`](src/memory/ft_bzero.c)	- zero a byte string.
- [`ft_memcpy`](src/memory/ft_memcpy.c)	- copy memory area.
- [`ft_memmove`](src/memory/ft_memmove.c)	- copy memory area.
- [`ft_strlcpy`](src/string/ft_strlcpy.c)	- copy string to an specific size.
- [`ft_strlcat`](src/string/ft_strlcat.c)	- concatenate string to an specific size.
- [`ft_strchr`](src/string/ft_strchr.c)	- locate character in string.
- [`ft_strrchr`](src/string/ft_strrchr.c)	- locate character in string.
- [`ft_strncmp`](src/string/ft_strncmp.c)	- compare two strings.
- [`ft_memchr`](src/memory/ft_memchr.c)	- scan memory for a character.
- [`ft_memcmp`](src/memory/ft_memcmp.c)	- compare memory areas.
- [`ft_strnstr`](src/string/ft_strnstr.c)	- locate a substring in a string.
- [`ft_strdup`](src/string/ft_strdup.c)	- creates a dupplicate for the string passed as parameter.

### Functions from `<stdlib.h>`
- [`ft_atoi`](src/string/ft_atoi.c)	- convert a string to an integer.
- [`ft_calloc`](src/memory/ft_calloc.c)	- allocates memory and sets its bytes' values to 0.

### Non-standard functions
- [`ft_substr`](src/string/ft_substr.c)	- returns a substring from a string.
- [`ft_strjoin`](src/string/ft_strjoin.c)	- concatenates two strings.
- [`ft_strtrim`](src/string/ft_strtrim.c)	- trims the beginning and end of string with specific set of chars.
- [`ft_split`](src/string/ft_split.c)	- splits a string using a char as parameter.
- [`ft_itoa`](src/string/ft_itoa.c)	- converts a number into a string.
- [`ft_strmapi`](src/string/ft_strmapi.c)	- applies a function to each character of a string.
- [`ft_striteri`](src/string/ft_striteri.c)	- applies a function to each character of a string.
- [`ft_putchar_fd`](src/write/ft_putchar_fd.c)	- output a char to a file descriptor.
- [`ft_putstr_fd`](src/write/ft_putstr_fd.c)	- output a string to a file descriptor.
- [`ft_putendl_fd`](src/write/ft_putendl_fd.c)	- output a string to a file descriptor, followed by a new line.
- [`ft_putnbr_fd`](src/write/ft_putnbr_fd.c)	- output a number to a file descriptor.

### Linked list functions

- [`ft_lstnew`](src/list/ft_lstnew.c)	- creates a new list element.
- [`ft_lstadd_front`](src/list/ft_lstadd_front.c)	- adds an element at the beginning of a list.
- [`ft_lstsize`](src/list/ft_lstsize.c)	- counts the number of elements in a list.
- [`ft_lstlast`](src/list/ft_lstlast.c)	- returns the last element of the list.
- [`ft_lstadd_back`](src/list/ft_lstadd_back.c)	- adds an element at the end of a list.
- [`ft_lstclear`](src/list/ft_lstclear.c)	- deletes and free list.
- [`ft_lstiter`](src/list/ft_lstiter.c)	- applies a function to each element of a list.
- [`ft_lstmap`](src/list/ft_lstmap.c)	- applies a function to each element of a list.

### Vector functions

- [`new_vector`](src/vector/new_vector.c) - create a new vector
- [`del_vector`](src/vector/del_vector.c) - delete a vector
- [`get_elem_vector`](src/vector/get_elem_vector.c) - return the element at the given index of the vector
- [`add_vector`](src/vector/add_vector.c) - add an element to a vector

### Get_next_line

- [`get_next_line`](src/get_next_line.c) - read a file line by line from th project [get_next_line](https://github.com/pyven-dr/get_next_line)
