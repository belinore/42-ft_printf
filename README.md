# 42-ft_printf

A 42 project to recreate the standard C `printf` function with formatted output and variable argument handling.

Function prototype:
```c
int ft_printf(const char *format, ...);
```
**Supported Conversions**
- `%c` — Character
- `%s` — String
- `%p` — Pointer address
- `%d` / `%i` — Signed decimal integer
- `%u` — Unsigned decimal integer
- `%x` / `%X` — Hexadecimal integer
- `%%` — Literal percent sign

## 🎯 Learning Outcomes

- Understanding of variadic functions
- Handling and formatting various data types
- Building modular and reusable output functions

## 📂 Project Structure

```
42-ft_printf/
├── ft_printf.c        # Core function logic
├── ft_*.c             # Helper functions
├── ft_printf.h        # Header file
├── Makefile           # Build automation
└── README.md          # Project documentation
```

## 🛠️ Compilation

To compile the library:

```bash
make            # Builds libftprintf.a
make clean      # Removes object files
make fclean     # Removes object files and libftprintf.a
make re         # Rebuilds everything
```

To use in another project:

```c
#include "ft_printf.h"
```

Then compile with:

```bash
gcc your_file.c -L. -lftprintf
```

## 📌 Notes

> ⚠️ **Norminette Compliance**  
> This project follows the [42 Norminette](https://github.com/42School/norminette) — a strict C coding style guide. It enforces rules like max 25 lines per function, separate declarations/assignments, and consistent formatting. Code is written for readability and structure over brevity.
