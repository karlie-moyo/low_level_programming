# UoS LOW LEVEL PROGRAMMING

![undraw_coding_re_iv62.svg](https://user-images.githubusercontent.com/110098940/219949766-01d150a7-a2cf-454d-958a-d61fe3ee7110.png)
This repository contains programs created for the _**Software Engineering** Programs._ Your girl here is ready for collaborations, Currently sharpening my knowledge and skills of C, Linux, Algorithms and Data Structures. Hey you! Come let's do hard things.This repository contains programs written for the low-level programming and algorithm track in the UoS Software Engineering Program. In these projects I learned about data structures, algorithms, and other low-level programming concepts while working in the C programming language. The following is a specific list of projects :


| PR.NO | PROJECT                                                                           | DESCRIPTION |
| ----- | --------------------------------------------------------------------------------- | ----------- |
| 0x00  | [C - Hello, World](./0x00-hello_world)                                            | A "Hello, World!" program in C is a basic example that uses the printf() function to display "Hello, World!" on the screen, demonstrating C program structure and syntax.            |
| 0x01  | [C - Variables, if, else, while](./0x01-variables_if_else_while)                  | Variables store data, if and else are used for conditional logic to execute code based on certain conditions, and while is a loop that repeatedly executes code as long as a specified condition is true.            |
| 0x02  | [C - Functions, nested loops](./0x02-functions_nested_loops)                      | Functions are reusable blocks of code that perform a specific task, while nested loops involve placing one loop inside another to perform repetitive tasks in multiple levels or dimensions.            |
| 0x03  | [C - Debugging](./0x03-debugging)                                                 | Debugging is the process of finding and fixing errors in a program to ensure it works correctly, using tools like debuggers and logs.             |
| 0x04  | [C - More functions, more nested loops](./0x04-more_functions_nested_loops)       | Functions are reusable blocks of code that perform specific tasks, while nested loops are loops inside other loops, used for tasks requiring multiple levels of iteration, like working with 2D arrays or complex data structures.            |
| 0x05  | [C - Pointers, arrays and strings](./0x05-pointers_arrays_strings)                | Pointers store memory addresses, allowing direct access to variables in memory. Arrays are collections of elements of the same type, and strings are arrays of characters terminated by a null character (`\0`). Pointers are often used with arrays and strings to manipulate data more efficiently.            |
| 0x06  | [C - More pointers, arrays and strings](./0x06-pointers_arrays_strings)           |  Together, pointers and arrays offer flexibility and efficiency in memory management, while strings, as arrays of characters, enable text manipulation.           |
| 0x07  | [C - Even more pointers, arrays and strings](./0x07-pointers_arrays_strings)      | Pointers store memory addresses, arrays are collections of elements, and strings are arrays of characters ending with a null character, often manipulated using pointers for efficient data handling.            |
| 0x08  | [C - Recursion](./0x08-recursion)                                                 | Recursion is a programming technique where a function calls itself to solve a problem. It breaks down complex tasks into simpler subproblems, typically with a base case to stop the recursion and prevent infinite calls.            |
| 0x09  | [C - Static libraries](./0x09-static_libraries)                                   | A static library is a collection of precompiled functions or code that are linked into a program during the compilation process, becoming part of the executable. It has a `.a` or `.lib` file extension and doesn't require external dependencies once compiled.            |
| 0x0A  | [C - argc, argv](./0x0A-argc_argv)                                                | `argc` is the number of command-line arguments passed to a program, and `argv` is an array of strings containing those arguments. `argv[0]` is the program's name, and `argv[1]`, `argv[2]`, etc., represent additional arguments.            |
| 0x0B  | [C - malloc, free](./0x0B-malloc_free)                                            | `malloc` allocates dynamic memory and returns a pointer, while `free` releases that memory when no longer needed to prevent memory leaks.           |
| 0x0C  | [C - More malloc, free](./0x0C-more_malloc_free)                                  | `malloc` allocates dynamic memory at runtime and returns a pointer to it, or `NULL` if allocation fails. Always check for `NULL` before using it, and free the memory with `free()` when done to prevent memory leaks.            |
| 0x0D  | [C - Preprocessor](./0x0D-preprocessor)                                           | The preprocessor in C handles tasks like macro substitution, file inclusion, and conditional compilation using directives such as `#define`, `#include`, and `#ifdef`, modifying the code before it is compiled.            |
| 0x0E  | [C - Structures, typedef](./0x0E-structures_typedef)                              | Structures in C group different data types into a single unit, while `typedef` creates an alias for an existing type, making the code more readable. For example, `typedef struct Person Person;` lets you use `Person` instead of `struct Person`.            |
| 0x0F  | [C - Function pointers](./0x0F-function_pointers)                                 | Function pointers in C store the address of a function, allowing dynamic function calls. They enable passing functions as arguments or storing them for later use, enhancing flexibility in code.            |
| 0x10  | [C - Variadic functions](./0x10-variadic_functions)                               | Variadic functions in C can accept a variable number of arguments, using macros from `stdarg.h` (`va_list`, `va_start`, `va_arg`, and `va_end`) to handle the arguments dynamically.            |
| 0x11  | [C - printf](https://github.com/karlie-moyo/printf)                               | The project focuses on building a custom printf function capable of handling multiple format specifiers and printing formatted output.           |
| 0x12  | [C - Singly linked lists](./0x12-singly_linked_lists)                             | Singly linked lists are a flexible, dynamic way to store data where each element points to the next, making insertion and deletion easy but traversal is only possible in one direction.            |
| 0x13  | [C - More singly linked lists](./0x13-more_singly_linked_lists)                   |  A singly linked list is a data structure where each node contains data and a pointer to the next node. It supports efficient insertions and deletions but only allows one-directional traversal, making random access slower. It's dynamic in size, but each node requires extra memory for the pointer.           |
| 0x14  | [C - Bit manipulation](./0x14-bit_manipulation)                                   | Bit manipulation involves using bitwise operators to directly modify individual bits of data, enabling efficient operations like setting flags, shifting bits, and optimizing memory usage. Common operators include AND, OR, XOR, NOT, and shift operations.            |
| 0x15  | [C - File io](./0x15-file_io)                                                     | File I/O in C allows programs to read from and write to files using functions like `fopen()`, `fread()`, `fwrite()`, and `fclose()`. It enables persistent data storage and retrieval, allowing interaction with external files.            |
| 0x16  | [C - Simple Shell](https://github.com/karlie-moyo/simple_shell)                 | The simple shell project involves creating a basic command-line interface that handles user input, parses commands, forks processes, and executes built-in or external programs. It focuses on understanding process management and system calls in a Unix-like environment.            |
| 0x17  | [C - Doubly Linked Lists](./0x17-doubly_linked_lists)                             | A doubly linked list is a data structure where each node contains data, a pointer to the next node, and a pointer to the previous node, allowing bidirectional traversal and efficient insertion/deletion at both ends. It requires extra memory for the `prev` pointer.            |
| 0x18  | [C - Dynamic libraries](./0x18-dynamic_libraries)                                 | Dynamic libraries are shared files that programs load at runtime, allowing code reuse and saving memory. They are linked during execution, not at compile time, and enable updates without recompiling the program. Common file extensions include `.so`, `.dll`, and `.dylib`.            |
| 0x19  | [C - Stacks, Queues - LIFO, FIFO](https://github.com/karlie-moyo/monty)         | Stacks (LIFO) and queues (FIFO) are data structures that manage the order of elements: stacks remove the last element added first (Last In, First Out), while queues remove the first element added first (First In, First Out). In the Monty Hall problem, these concepts are not directly used but can be applied in decision-making simulations.            |
| 0x1A  | [C - Hash tables](./0x1A-hash_tables)                                             | A hash table is a data structure that stores key-value pairs, allowing fast retrieval using a hash function to map keys to indices. It handles collisions through techniques like chaining or open addressing. Hash tables provide average O(1) time complexity for insert, search, and delete operations.            |
| 0x1B  | [C - Sorting algorithms & Big O](https://github.com/karlie-moyo/sorting_algorithms)  | Merge Sort, Quick Sort, and Heap Sort are the most commonly used efficient sorting algorithms, with O(n log n) time complexity in the average case. The choice of algorithm depends on the dataset size, stability, and specific use case requirements. |           
| 0x1C  | [C - Makefiles](./0x1C-makefiles)                                                 | File handling in C allows programs to interact with files using functions like `fopen()`, `fclose()`, `fread()`, `fwrite()`, and `fprintf()`. These functions enable reading, writing, and manipulating file data.            |
| 0x1D  | [C - Binary trees](https://github.com/karlie-moyo/binary_trees)                   | A binary tree is a hierarchical data structure where each node has at most two children, a left and a right. It's used in algorithms like searching and sorting. Types include full, complete, balanced, and binary search trees (BSTs). Common operations are insertion, deletion, and traversal (pre-order, in-order, post-order, level-order).           |
| 0x1E  | [C - Search Algorithms](./0x1E-search_algorithms)                                 | Search algorithms find elements in data structures. Key types include **Linear Search** (O(n)), **Binary Search** (O(log n) for sorted data), **BFS/DFS** for graph traversal (O(V + E)), **Hashing** (O(1) average), **Jump Search** (O(√n)), and **Interpolation Search** (O(log log n) for uniformly distributed data).             |

### AUTHOR:
<details>
    <summary>KARLIE MOYO</summary>
    <ul>
        <li>
            <a href="https://github.com/karlie-moyo">Github</a>
        </li>
        <li>
            <a href="https://twitter.com/karlieemoyo">Twitter</a>
        </li>
        <li>
            <a href="https://karlieemoyo@gmail.com">e-mail</a>
        </li>
    </ul>
</details>

---

### Acknowledgements  :pray:
___
All of the work in this project was conducted as part of the UoS-SE program's curriculum.
