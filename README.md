# libft

42 project aims to develop my personalized library of functions written in C.

| function name  |  prototype | description  |
| :------------ | -------------------------|------------------------|
| ft_ isalpha   | int ft_isalpha(int c) |this function mimics the behavior of isalpha, taking a character as a parameter and returning 0 if it is not an alphabetic character.|
| ft_isdigit      | int ft_isdigit(int c) |This function mimics the behavior of isdigit, taking an integer as a parameter and returning 0 if it is not a numeric character.       |
| ft_isalnum | int ft_isalnum(int c) |This function mimics the behavior of isalnum, taking an integer as a parameter and returning 0 if it is not an alphanumeric character. |
| ft_isascii | int ft_isascii(int c) |This function mimics the behavior of isascii, taking an integer as a parameter and returning 0 if it does not fit into the ASCII character set. |
|ft_isprint | int ft_isprint(int c) |This function mimics the behavior of isprint, taking an integer as a parameter and returning 0 if it is not a printable character. |
ft_strlen | size_t ft_strlen(const char *str) |This function mimics the behavior of strlen, taking a string as a parameter and returning its size. |
| ft_memset | void    *ft_memset(void *s, int c, size_t n) |This function mimics the behavior of memset, filling the first n bytes of the memory area pointed to by s with the constant byte c, and returning a pointer to the memory area |
|ft_bzero | void ft_bzero(void *s, size_t n) | This function mimics the behavior of bzero, erasing the data in the n bytes of memory starting at the location pointed to by s by writing zeros (bytes containing '\0') to that area |
|ft_memcpy | void    *ft_memcpy(void *dest, const void *src, size_t n) | "This function mimics the behavior of memcpy, copying n bytes from the memory area src to the memory area dest, and returning a pointer to dest. |
| ft_memmove | void    *ft_memmove(void *dest, const void *src, size_t n) | This function mimics the behavior of memmove, performing the same operation as memcpy, but taking into account memory spaces that overlap. |
ft_strlcpy | size_t  ft_strlcpy(char *dst, const char *src, size_t size) | This function copies a string and returns its length. |
| ft_strlcat | size_t  ft_strlcat(char *dst, const char *src, size_t size) |This function mimics the behavior of strlcat, concatenating strings and returning the length of the resulting string |