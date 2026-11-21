# C++ Modules

A collection of C++ learning exercises organized into modules 00–04. Each exercise has its own source files and Makefile.

| Module | Topics in the checked-in exercises |
| --- | --- |
| `module00` | Basic programs, phone book classes, and accounts |
| `module01` | Allocation, references, files, and class interaction |
| `module02` | Fixed-point numbers, operators, and points |
| `module03` | Inheritance through the ClapTrap family |
| `module04` | Polymorphism, abstract interfaces, and object ownership |

## Build and run an exercise

Requires Make and a C++ compiler. For example, module 00 exercise 00 uses C++98 with warnings treated as errors:

```sh
make -C module00/ex00
./module00/ex00/megaphone "Hello, world!"
```

For other exercises, run Make in their directory and check that Makefile's `NAME` variable for the executable name. There is no root Makefile to build every module.

```sh
make -C module00/ex00 clean
make -C module00/ex00 fclean
```

These are individual learning exercises; their `main.cpp` or `tests.cpp` files provide examples for the corresponding classes.
