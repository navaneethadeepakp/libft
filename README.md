# Libft

A custom C static library (`libft.a`) recreating essential standard C library functions from scratch. This project demonstrates a strong foundation in low-level memory management, pointer arithmetic, and data structure implementation.

## Technical Highlights

*   **Memory & State Management:** Implements secure string operations and memory manipulations, such as dynamic substring extraction (`ft_substr`) with strict size bounding and allocation checking.
*   **Custom Data Structures:** Features a complete suite of functions for managing singly linked lists utilizing a custom `t_list` struct, including node creation, mapping, and memory-safe clearing.
*   **Character Processing:** Includes fundamental character validation and transformation utilities, such as converting characters between cases natively (`ft_tolower`, `ft_toupper`).
*   **Strict Compilation Standards:** Built via a `Makefile` that enforces `-Wall -Wextra -Werror` compiler flags to guarantee clean, warning-free code.

## Build & Integration

The project uses a standard `Makefile` to compile the source code into a static library archive.

**1. Compile the Library**

```bash
make
```

To compile the library with the additional linked list data structure functions, run:

```bash
make bonus
```

**2. Link During Compilation**

Compile your main by linking the generated static library:

```bash
cc your_file.c libft.a
```
