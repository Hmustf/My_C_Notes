# C Programming Language Keywords

C has a set of reserved keywords that have special meanings and cannot be used as identifiers in programs. Here's a comprehensive list of all C keywords organized by categories:

## Data Types
- `int` - Integer data type
- `char` - Character data type
- `float` - Single-precision floating-point
- `double` - Double-precision floating-point
- `void` - Empty data type/no return value
- `_Bool` - Boolean data type (C99)
- `long` - Long integer data type
- `short` - Short integer data type
- `signed` - Signed modifier
- `unsigned` - Unsigned modifier

## Storage Classes
- `auto` - Automatic storage duration
- `register` - Register storage class
- `static` - Static storage duration
- `extern` - External linkage

## Control Flow
- `if` - Conditional statement
- `else` - Alternative branch in conditional
- `switch` - Multi-way decision
- `case` - Label in switch statement
- `default` - Default label in switch
- `break` - Exit from loop/switch
- `continue` - Skip to next iteration
- `return` - Return from function
- `goto` - Jump to label

## Loops
- `for` - For loop
- `while` - While loop
- `do` - Do-while loop

## Type Qualifiers
- `const` - Constant value
- `volatile` - Value may change unexpectedly
- `restrict` - Pointer optimization hint (C99)

## Structure and Union
- `struct` - Structure declaration
- `union` - Union declaration
- `typedef` - Create type alias
- `enum` - Enumeration declaration

## Size and Alignment
- `sizeof` - Size of type/variable
- `_Alignas` - Specify alignment (C11)
- `_Alignof` - Query alignment (C11)

## Complex Numbers (C99)
- `_Complex` - Complex number type
- `_Imaginary` - Imaginary number type

## Atomic Operations (C11)
- `_Atomic` - Atomic type specifier

## Thread Local Storage (C11)
- `_Thread_local` - Thread-local storage

## Function Specifiers
- `inline` - Inline function hint (C99)
- `_Noreturn` - Function does not return (C11)

## Notes:
1. Keywords are case-sensitive
2. Cannot be used as identifiers (variable names, function names, etc.)
3. Some keywords were introduced in later C standards (C99, C11)
4. Different compilers might support additional keywords

## Best Practices:
1. Always use keywords according to their intended purpose
2. Be aware of which C standard your compiler supports
3. Some keywords might behave differently across different platforms
4. Avoid using names that are too similar to keywords for better code readability
