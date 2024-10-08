# Derivative Calculator made with MIPS Assembly

This simple derivative calculator was written in MIPS Assembly using the MARS MIPS Simulator. 

The basic differentiation rules include (1) Constant rule, (2) Power rule, (3) Sum rule, 
(4) Difference rule, and (5) Constant multiple rule. 

## Valid inputs
- Integers
- Minus sign (-) and plus sign (+)
- Variable 'x' character in lowercase.
- Caret symbol (^, to denote exponents). 
- The character length is limited to up to 12 characters. An error prompt will appear if exceeded. This is to help limit the user
from inputting large values that are not within -127 to 127.

## Invalid Inputs 
- Leading or trailing character that is not an integer (except when representing a negative value e.g., -4x+6).
- Floating-point numbers
- Ambiguous inputs. Example: 4x++++6^5, 4x4^, and etc. 
- Characters that are not valid inputs. Example: @, !, ~, a, and etc.

## Limitations
- Arithmetic operations only work on values from -127 to 127 due to the limitations of the signed char. The program
may not output the values correctly if the inputs/results are outside the said constraints.
- Functions should follow the standard form. Functions in standard form are written in descending order of power wherein the highest power
should be first and the lowest power should be last. For example, the function 4x^-5-5+6x^2 written in 
standard form is 4x^5+6x^2-5. Otherwise, the program may not output the correct result.


## Author
Carl Joseph P. Mate and Sophia Marie C. Casas



