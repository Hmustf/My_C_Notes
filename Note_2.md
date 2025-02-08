# C Programming Language Fundamentals

## Tokens and Basic Elements in C

### Token
- A token is the smallest individual unit or element in a C program that has meaning to the compiler
- In C, there are five types of tokens:
  1. Keywords
  2. Identifiers
  3. Constants
  4. String Literals
  5. Operators and Special Symbols
- The C compiler identifies these tokens during lexical analysis

### Tokenizing
- Tokenizing (or lexical analysis) is the first phase of C compilation
- The C preprocessor and lexical analyzer process the source code to identify tokens
- Comments and whitespace are typically removed during this phase
- Example: `int main(void)` is broken into tokens: `int` (keyword), `main` (identifier), `(` (delimiter), `void` (keyword), `)` (delimiter)

### Keyword
- C has 32 reserved keywords that cannot be used as identifiers
- Common C keywords include:
  - Data types: `int`, `char`, `float`, `double`, `void`
  - Control flow: `if`, `else`, `for`, `while`, `do`, `switch`, `case`, `break`, `continue`, `return`
  - Storage classes: `auto`, `static`, `extern`, `register`
  - Type qualifiers: `const`, `volatile`

### Identifier
- Names for variables, functions, structures, unions, and labels in C
- Rules in C:
  - Must start with a letter or underscore
  - Can contain letters, digits, and underscores
  - Case sensitive (`count` ≠ `Count`)
  - Cannot use C keywords
- Examples: 
  - Valid: `main`, `_temp`, `counter1`, `studentMarks`
  - Invalid: `2count`, `while`, `my-var`

### Operator
- C operators by category:
  - Arithmetic: `+`, `-`, `*`, `/`, `%` (integer division and modulo in C)
  - Increment/Decrement: `++`, `--` (unique to C and C-like languages)
  - Relational: `>`, `<`, `>=`, `<=`, `==`, `!=`
  - Logical: `&&`, `||`, `!`
  - Bitwise: `&`, `|`, `^`, `~`, `<<`, `>>`
  - Assignment: `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `<<=`, `>>=`, `&=`, `^=`, `|=`
  - Special: `sizeof`, `&` (address-of), `*` (pointer), `.` (member), `->` (pointer member)

### Constant
- C supports several types of constants:
  - Integer constants:
    - Decimal: `123`, `-456`
    - Octal: `0777`
    - Hexadecimal: `0xFF`, `0xA5`
  - Floating-point constants: `3.14`, `2.0e-4`
  - Character constants: `'A'`, `'\n'`, `'\0'`
  - Enumeration constants
  - Defined constants (`#define MAX 100`)
  - `const` qualified variables

### String Literal
- In C, string literals are arrays of characters terminated by null character (`\0`)
- Enclosed in double quotes: `"Hello, World!"`
- C string escape sequences:
  - `\n` - newline
  - `\t` - tab
  - `\r` - carriage return
  - `\b` - backspace
  - `\\` - backslash
  - `\"` - double quote
  - `\0` - null character
- String concatenation: `"Hello " "World"` is same as `"Hello World"`

### Delimiter
- Special symbols in C:
  - Semicolon (`;`) - statement terminator
  - Parentheses (`()`) - function calls, expressions, parameter lists
  - Braces (`{}`) - compound statements, function bodies, structure/union declarations
  - Square brackets (`[]`) - array subscripts
  - Comma (`,`) - separator in function arguments and variable declarations
  - Preprocessor symbols (`#`) - for preprocessor directives
  - Comments:
    - Single line: `//`
    - Multi-line: `/* */`
