# Ft_printf

This project is a reproduction of the printf function

## Installation

Once you clone the repository, you just need to include the library in the project's library, to compute only the folder.

## Use

To use this project, you just need to call the function:
- ft_printf("message %"what you need", variable");
this function contains: 

## Supported conversions (ft_printf — without bonus)

| Conversion | Description                                   | Example call             | Example output         |
|------------|-----------------------------------------------|---------------------------|--------------------------|
| `%c`       | Prints a single character                      | `ft_printf("%c", 'A')`    | `A`                      |
| `%s`       | Prints a string                                | `ft_printf("%s", "42")`   | `42`                     |
| `%p`       | Prints a pointer address in hexadecimal        | `ft_printf("%p", ptr)`    | `0x7ffeefbff618`         |
| `%d`       | Prints a signed integer (base 10)              | `ft_printf("%d", -42)`    | `-42`                    |
| `%i`       | Same as `%d`                                   | `ft_printf("%i", 42)`     | `42`                     |
| `%u`       | Prints an unsigned integer (base 10)           | `ft_printf("%u", 42)`     | `42`                     |
| `%x`       | Prints a number in lowercase hexadecimal       | `ft_printf("%x", 255)`    | `ff`                     |
| `%X`       | Prints a number in uppercase hexadecimal       | `ft_printf("%X", 255)`    | `FF`                     |
| `%%`       | Prints a literal percent sign `%`              | `ft_printf("%%")`         | `%`                      |


## Author

MILLET Mehdi
