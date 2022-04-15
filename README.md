# ft_printf
Own limited implementation of printf.

## Allowed types
Implemented the following conversions:
- %c Prints a single character.
- %s Prints a string (as defined by the common C convention).
- %p The void * pointer argument has to be printed in hexadecimal format.
- %d Prints a decimal (base 10) number.
- %i Prints an integer in base 10.
- %u Prints an unsigned decimal (base 10) number.
- %x Prints a number in hexadecimal (base 16) lowercase format.
- %X Prints a number in hexadecimal (base 16) uppercase format.
- %% Prints a percent sign.

## Usage
1. Build a project using Makefile

   ```sh
   $ make
   ```

2. Include a header to .c files:

    ```
   #include "ft_printf.h"
   ```

3. Compile your program, like this:

   ```sh
   $ gcc *.c libftprintf.a
   ```