📚 Libft – A C Standard Library Reimagined

Reimplementation of the standard C library as a foundational project at 42.

🚀 About the project

This project is the very first technical challenge at 42. Its purpose is to build a personal library of utility functions in C by reimplementing common libc functions and creating additional ones that will be useful throughout the program.

The goal is to gain a deep understanding of how low-level operations work, especially memory manipulation and string processing, and how to build and manage a C static library from scratch.

⚙️ Technologies

Language: C

Compiler: cc with flags -Wall -Wextra -Werror

Build System: Makefile

Style: 42 Norminette

🧩 Project Structure

libft.h – Header file with all function prototypes

ft_*.c – Implementation files

Makefile – Automates compilation

🛠️ Functions Implemented

✅ Part 1 – Libc Reimplementations

ft_isalpha, ft_isdigit, ft_isalnum, ft_isascii, ft_isprint

ft_strlen, ft_memset, ft_bzero, ft_memcpy, ft_memmove

ft_strlcpy, ft_strlcat, ft_toupper, ft_tolower

ft_strchr, ft_strrchr, ft_strncmp, ft_memchr, ft_memcmp, ft_strnstr

ft_atoi, ft_calloc, ft_strdup

🔧 Part 2 – Additional Functions

ft_substr, ft_strjoin, ft_strtrim, ft_split

ft_itoa, ft_strmapi, ft_striteri

ft_putchar_fd, ft_putstr_fd, ft_putendl_fd, ft_putnbr_fd

🧪 Bonus – Linked List Functions

ft_lstnew, ft_lstadd_front, ft_lstsize, ft_lstlast

ft_lstadd_back, ft_lstdelone, ft_lstclear, ft_lstiter, ft_lstmap

📦 How to Compile

make        # compiles libft and generates libft.a
make clean  # removes object files
make fclean # removes object files and libft.a
make re     # rebuilds everything from scratch
make bonus  # compiles bonus part as well

✅ Results

✅ 100% of required functions implemented and working

✅ Tested with libft-unit-test and libft-tester

🧠 What I Learned

Manual memory management in C

Writing and organizing Makefiles

Static functions and modular programming

Creating and managing static libraries with ar

📁 Directory Structure

.
├── ft_*.c
├── libft.h
├── Makefile
├── libft.a
└── README.md

🧪 Testing

# Example: running libft-unit-test
$ git clone https://github.com/alelievr/libft-unit-test.git
$ cd libft-unit-test
$ make f

📞 Contact

📧 diogo.dc.viegas@gmail.com🌐 LinkedIn (optional)

🏁 Status: Completed ✅

