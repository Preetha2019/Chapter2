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
### C’s int limits identifiers, from limits.h:
#### Identifier- Value- Description
* _char types_
* CHAR_BIT- 8- Number of bits in a char type
* SCHAR_MIN- –127- Minimum signed char type
* SCHAR_MAX- 127- Maximum signed char type
* UCHAR_MAX- 255- Maximum unsigned char type
* CHAR_MIN- SCHAR_MIN- Minimum char value, if characters are unsigned
* CHAR_MAX- SCHAR_MAX- Maximum char value, if characters are unsigned
* CHAR_MIN- 0- If characters are signed
* CHAR_MAX- UCHAR_MAX- If characters are signed
* MB_LEN_MAX- 1- Maximum number of bytes in multibyte char
* _short int types_
* SHRT_MIN- –32767- Minimum (signed) short type
* SHRT_MAX- 32767- Maximum (signed) short type
* USHRT_MAX- 65535- Maximum unsigned short type
* INT_MIN- –32767- Minimum (signed) int type
* INT_MAX- 32767- Maximum (signed) int type
* UINT_MAX- 65535- Maximum unsigned int type
* _long int types_
* LONG_MIN- –2147483647- Minimum (signed) long type
* LONG_MAX- 2147483647- Maximum (signed) long type
* ULONG_MAX- 4294967295- Maximum unsigned long type
#### Hint:
* Other identifiers generally are defined in float.h
* Rather than code constants for these values into your program, you should use
one of the predefined identifiers listed in limits.h and float.h files. These identifiers allow
for better portability and make the meaning of your program clear.
### Constants:
All homes are buildings, but not all buildings are homes. All literals are _constants_, but
_not all constants are literals_.
__Example:__
(img scr"https://photos.app.goo.gl/7GUBujTazSkqNuxp9")



