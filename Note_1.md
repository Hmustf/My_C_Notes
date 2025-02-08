# C Programming Language Keywords

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

## Complete Keywords Reference Table

| Keyword | Category | Description | Standard |
|---------|----------|-------------|-----------|
| `auto` | Storage Class | Automatic storage duration | C89 |
| `break` | Control Flow | Exit from loop/switch | C89 |
| `case` | Control Flow | Label in switch statement | C89 |
| `char` | Data Type | Character data type | C89 |
| `const` | Type Qualifier | Constant value | C89 |
| `continue` | Control Flow | Skip to next iteration | C89 |
| `default` | Control Flow | Default label in switch | C89 |
| `do` | Loop | Do-while loop | C89 |
| `double` | Data Type | Double-precision floating-point | C89 |
| `else` | Control Flow | Alternative branch in conditional | C89 |
| `enum` | Structure | Enumeration declaration | C89 |
| `extern` | Storage Class | External linkage | C89 |
| `float` | Data Type | Single-precision floating-point | C89 |
| `for` | Loop | For loop | C89 |
| `goto` | Control Flow | Jump to label | C89 |
| `if` | Control Flow | Conditional statement | C89 |
| `int` | Data Type | Integer data type | C89 |
| `long` | Data Type | Long integer data type | C89 |
| `register` | Storage Class | Register storage class | C89 |
| `return` | Control Flow | Return from function | C89 |
| `short` | Data Type | Short integer data type | C89 |
| `signed` | Data Type | Signed modifier | C89 |
| `sizeof` | Operator | Size of type/variable | C89 |
| `static` | Storage Class | Static storage duration | C89 |
| `struct` | Structure | Structure declaration | C89 |
| `switch` | Control Flow | Multi-way decision | C89 |
| `typedef` | Structure | Create type alias | C89 |
| `union` | Structure | Union declaration | C89 |
| `unsigned` | Data Type | Unsigned modifier | C89 |
| `void` | Data Type | Empty data type | C89 |
| `volatile` | Type Qualifier | Value may change unexpectedly | C89 |
| `while` | Loop | While loop | C89 |
| `_Bool` | Data Type | Boolean data type | C99 |
| `_Complex` | Data Type | Complex number type | C99 |
| `_Imaginary` | Data Type | Imaginary number type | C99 |
| `inline` | Function | Inline function hint | C99 |
| `restrict` | Type Qualifier | Pointer optimization hint | C99 |
| `_Alignas` | Alignment | Specify alignment | C11 |
| `_Alignof` | Alignment | Query alignment | C11 |
| `_Atomic` | Type Qualifier | Atomic type specifier | C11 |
| `_Noreturn` | Function | Function does not return | C11 |
| `_Thread_local` | Storage Class | Thread-local storage | C11 |
