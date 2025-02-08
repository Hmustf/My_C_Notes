# Number Systems in C Programming

## 1. Decimal (Base-10)
- This is the number system we use in everyday life
- Uses digits 0-9
- Example: 125 = 1×10² + 2×10¹ + 5×10⁰
- In C, decimal numbers are written as is: `int num = 125;`

## 2. Octal (Base-8)
- Uses digits 0-7
- In C, octal numbers start with '0'
- Example: 0125 (octal) = 1×8² + 2×8¹ + 5×8⁰ = 85 (decimal)
- Common use cases: file permissions in Unix/Linux

## 3. Hexadecimal (Base-16)
- Uses digits 0-9 and letters A-F (or a-f)
- A=10, B=11, C=12, D=13, E=14, F=15
- In C, hexadecimal numbers start with '0x' or '0X'
- Example: 0x7B = 7×16¹ + 11×16⁰ = 123 (decimal)
- Common use cases: 
  - Memory addresses
  - Color codes (e.g., #FF0000 for red)
  - Binary data representation

## 4. Binary (Base-2)
- Uses only 0 and 1
- In C, binary literals start with '0b' (in C23 standard)
- Example: 0b1111 = 1×2³ + 1×2² + 1×2¹ + 1×2⁰ = 15 (decimal)

## Number System Conversion in C

### Printf Format Specifiers
```c
int num = 125;
printf("%d",  num);    // Decimal: 125
printf("%o",  num);    // Octal: 175
printf("%x",  num);    // Hexadecimal: 7d
printf("%X",  num);    // Hexadecimal: 7D
```

### Reading Different Number Systems
```c
int a, b, c;
scanf("%d", &a);  // Read decimal
scanf("%o", &b);  // Read octal
scanf("%x", &c);  // Read hexadecimal
```

## Tips and Tricks
1. To identify number systems in code:
   - No prefix = Decimal
   - '0' prefix = Octal
   - '0x' or '0X' prefix = Hexadecimal
   - '0b' prefix = Binary (C23)

2. Common Memory Units
   - 1 Byte = 8 bits
   - 1 Kilobyte (KB) = 1024 bytes
   - 1 Megabyte (MB) = 1024 KB
   - 1 Gigabyte (GB) = 1024 MB

3. Bitwise Operations
   - Often used with hexadecimal numbers
   - Useful for:
     - Flag manipulation
     - Hardware interaction
     - Memory optimization
     - Bit masking

## Common Use Cases
1. Decimal
   - General purpose calculations
   - User input/output
   - Mathematical operations

2. Octal
   - Unix file permissions
   - Legacy systems

3. Hexadecimal
   - Memory addresses
   - Color codes
   - Binary file formats
   - Network protocols
   - Debugging

4. Binary
   - Low-level programming
   - Hardware interfaces
   - Bitwise operations
