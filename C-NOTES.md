# C NOTES by Vinnie - Eldoret
### My Reading Notes - Type Conversion & Operators

#### 1. TYPE CONVERSION
Changing one data type to another.

**a) Implicit (Automatic):**
Compiler does it. Small -> Big
int -> float, char -> int
Example: int a=10; float b=a; // b=10.0

**b) Explicit (Casting):**
You force it. (type) value
Example: float m=89.9; int n=(int)m; // n=89

USE: When you want correct division
int a=7, b=2;
float ans = (float)a / b; // 3.5 not 3

#### 2. C OPERATORS

1. Arithmetic: + - * / %
   % = remainder. Example 10%3=1

2. Assignment: = += -= *= /= %=
   x+=5 means x=x+5

3. Relational: == != > < >= <=
   Returns 1 (true) or 0 (false)
   Example: if (marks >=50)

4. Logical: && || !
   && = AND, || = OR, ! = NOT
   Example: if (a>0 && b>0)

5. Increment/Decrement: ++ --
   a++ = a=a+1

6. Ternary: condition ? true : false
   Example: int pass = (marks>50)?1:0;

#### 3. IMPORTANT RULES
- int/int = int. So 5/2=2. Use (float)5/2=2.5
- == is for comparison, = is for assignment. Don't mix!
- Always use correct type in printf: %d for int, %f for float, %c for char

---
Written on: 7th Oct 2026 Morning - Eldoret
Next: Calculator Project
