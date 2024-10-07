### README.md for CERVIII/Libft

#### Project Description
The `libft` project is part of the 42 school. It is a custom implementation of the standard C library, providing a set of common C functions that are often needed in programming.

#### Features
- Custom implementations of standard C library functions such as `memset`, `bzero`, `memcpy`, `memmove`, `strlen`, `strlcpy`, `strlcat`, `strchr`, `strrchr`, `strnstr`, `strcmp`, `atoi`, and more.
- Additional utility functions like `ft_split`, `ft_strjoin`, `ft_strtrim`, `ft_itoa`, `ft_substr`, etc.
- Linked list manipulation functions including `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`, `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`.

#### Usage
To use the library, compile it and link it with your project:
```bash
make
```

Include the header file `libft.h` in your C source files:
```c
#include "libft.h"
```

Link the compiled library when building your project:
```bash
gcc -o my_program my_program.c -L. -lft
```
