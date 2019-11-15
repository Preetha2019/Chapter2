# CHAPTER 2 DATA TYPES, CONSTANTS, VARIABLES AND ARRAYS
### Data Types:
* The C language supports a number of data types.
* Because most CPUs generally support these data types directly, it is
unnecessary for the compiler to convert the data types into the types the CPU
understands. 
* C provides the mechanisms to create and use types of data created by the programmer.
### C's Data Types:
#### Type- Size- Description:
* char- 1- byte Used for characters or integer variables.
* int- 2 or 4- bytes Used for integer values.
* float- 4- bytes Floating-point numbers.
* double- 8- bytes Floating-point numbers.
### C’s Data Type Modifiers:
##### Modifier- Description
* long- Forces a type int to be 4 bytes (32 bits) long and forces a type
* double- to be larger than a double (but the actual size is implementation defined). Cannot be used with short.
* short- Forces a type int to be 2 bytes (16 bits) long. Cannot be used
with long.
* unsigned- Causes the compiler (and CPU) to treat the number as containing only positive values. Because a 16-bit signed integer can
hold values between –32,768 and 32,767, an unsigned integer can hold values between 0 and 65,535. The unsigned modifier can be used with char, long, and short (integer) types.
#### Hint:
* A number of useful identifiers are defined in the limits.h header file in ANSI C.
* Use limits.h so that predefined identifiers can define the limits for the integer data types.
