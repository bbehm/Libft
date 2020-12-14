# Libft

__My personal function library where I have recreated some well-known functions__

### Usage

- Clone the repo and navigate to the root of the folder
- Run `make`
- If you want to delete the created __.o__ files run `make clean`
- Now you have a `libft.a` file at the root of the repo which is the compiled library ready to be used

### Examples of what you can find in the library ...

__ft_memccpy__: copies no more than n bytes from memory area src to memory area dest, stopping when the character c is found.
```c
void	*ft_memccpy(void *dst, const void *src, int c, size_t n);
```
__ft_striteri__: applies the function 'f' that takes parameter 'i' to each character of the string passed as argument.
```c
void	ft_striteri(char *s, void (*f)(unsigned int, char *));
```
__ft_lstnew__: creates a new linked list instance
```c
t_list	*ft_lstnew(void const *content, size_t content_size);
```

```c
typedef struct  s_list
{
	void  *content;
	size_t  content_size;
	struct s_list	*next;
} t_list;
```
### ... plus many more functions!
