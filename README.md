![image](https://github.com/user-attachments/assets/a5bdfa58-ba32-42e9-a57d-b79ec0ffb6e7)

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
| ft_toupper | int ft_toupper(int c) | Convert the parameter to an uppercase letter if it is a lowercase letter; otherwise, return c. |
| ft_tolower | int     ft_tolower(int c) | Convert the parameter to a lowercase letter if it is an uppercase letter; otherwise, return c. |
| ft_strchr | char    *ft_strchr(const char *s, int c) | This function mimics the behavior of strchr, returning a pointer to the first occurrence of the character c in the string s. |
| ft_strrchr | char    *ft_strrchr(const char *s, int c) | This function mimics the behavior of strrchr, returning a pointer to the last occurrence of the character c in the string s. |
| ft_strncmp | int     ft_strncmp(const char *s1, const char *s2, size_t n) | This function mimics the behavior of strncmp, comparing the two strings s1 and s2, and returning an integer indicating the result of the comparison as follows: 0 if s1 and s2 are equal, a negative value if s1 is less than s2, and a positive value if s1 is greater than s2 |
ft_memchr | void    *ft_memchr(const void *s, int c, size_t n) | This function mimics the behavior of memchr, scanning the initial n bytes of the memory area pointed to by s for the first occurrence of the character c. |
ft_memcmp | int     ft_memcmp(const void *s1, const void *s2, size_t n) | This function mimics the behavior of memcmp, comparing the first n bytes of the memory areas s1 and s2, and returning an integer less than, equal to, or greater than zero if the first n bytes of s1 are found, respectively, to be less than, to match, or be greater than the first n bytes of s2. |
ft_strnstr | char    *ft_strnstr(const char *big, const char *little, size_t len) | This function mimics the behavior of strnstr, locating a substring in a string. |
ft_atoi | int     ft_atoi(const char *nptr) | This function mimics the behavior of atoi, converting a string to an integer. |
ft_calloc | void    *ft_calloc(size_t nmemb, size_t size) | This function mimics the behavior of calloc, which allocates memory for an array of nmemb elements, each with a size of bytes, and returns a pointer to the allocated memory. The memory is initialized to zero. |
ft_strdup | char    *ft_strdup(const char *s) | This function mimics the behavior of strdup, returning a pointer to a new string that is a duplicate of the string s. |
ft_substr | char *ft_substr(char const *s, unsigned int start, size_t len) | This function allocates memory using malloc and returns a substring from the string 's'. The substring starts at index 'start' and has a maximum size of 'len'. |
ft_strjoin | char *ft_strjoin(char const *s1, char const *s2) | This function allocates memory using malloc and returns a new string, which is the result of concatenating 's1' and 's2' |
ft_strtrim | char *ft_strtrim(char const *s1, char const *set) | This function allocates memory using malloc and returns a copy of 's1' with the characters specified in 'set' removed from the beginning and the end of the string. |
ft_split | char **ft_split(char const *s, char c) | This function allocates memory using malloc and returns an array of strings obtained by splitting 's' using the character 'c' as a delimiter. The array is terminated with a NULL pointer. |
ft_itoa | char *ft_itoa(int n) | This function allocates memory using malloc and returns a string representing the integer received as an argument. |
ft_strmapi | char *ft_strmapi(char const *s, char (*f)(unsigned int, char)) | This function applies the function 'f' to each character of the string 's', passing its index as the first argument, and creates a new string (using malloc) resulting from successive applications of 'f'. |
ft_striteri | void ft_striteri(char *s, void (*f) (unsigned int, char*)) | This function applies the function 'f' to each character of the string passed as an argument, passing its index as the first argument. Each character is passed by address to 'f' to be modified if necessary. |
ft_putchar_fd | void ft_putchar_fd(char c, int fd) | This function outputs the character 'c' to the given file descriptor.|
ft_putstr_fd | void ft_putstr_fd(char *s, int fd) | This function outputs the string 's' to the given file descriptor. |
ft_putendl_fd | void ft_putendl_fd(char *s, int fd) | This function outputs the string 's' to the given file descriptor, followed by a newline. |
ft_putnbr_fd | void ft_putnbr_fd(int n, int fd) | This function outputs the integer 'n' to the given file descriptor. 



## **Bonus part**

| function name  |  prototype | description  |
| :------------ | -------------------------|------------------------|
ft_lstnew | t_list *ft_lstnew(void *content) | This function allocates memory using malloc and returns a new node. The member variable 'content' is initialized with the value of the parameter 'content', and the variable 'next' is initialized to NULL. |
ft_lstadd_front | void ft_lstadd_front(t_list **lst, t_list *new) | This function adds the node 'new' at the beginning of the list. |
ft_lstsize | int ft_lstsize(t_list *lst) | Counts the number of nodes in a list. |
ft_lstlast | t_list *ft_lstlast(t_list *lst) | Returns the last node of the list. | 
ft_lstadd_back | void ft_lstadd_back(t_list **lst, t_list *new) | Adds the node ’new’ at the end of the list. |
ft_lstdelone | void ft_lstdelone(t_list *lst, void (*del)(void *)) | This function takes a node as a parameter and frees the memory of the node's content using the function 'del' provided as a parameter. It then frees the node itself. The memory of 'next' must not be freed. |
ft_lstclear | void ft_lstclear(t_list **lst, void (*del)(void *)) |  This function deletes and frees the given node and every successor of that node, using the function 'del' and free. |
ft_lstiter | void ft_lstiter(t_list *lst, void (*f)(void *)) | This function iterates through the list 'lst' and applies the function 'f' to the content of each node. |
ft_lstmap | t_list *ft_lstmap(t_list *lst, void *(*f)(void *), void (*del)(void *)) | This function iterates through the list 'lst' and applies the function 'f' to the content of each node. It creates a new list resulting from the successive applications of the function 'f'. The 'del' function is used to delete the content of a node if needed.



## Usage
We can utilize the Makefile, employing the 'make' command to link the functions into an archive file named libft.a.

```
make
```
Using 'make' by itself will create libft.a without the bonus part. To include the bonus part, use 'make bonus'.

```
make bonus
```
You can clean your directory and delete the object files by using 'make clean'
```
make clean
```
Using 'make fclean' will also remove the libft.a file.

```
make fclean
```
