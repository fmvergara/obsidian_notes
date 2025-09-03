A variable can be of the following types:
1. Local Variable
2. Global Variable
3. Static Variable
```
static int counter = 0; // persists across function calls
```
4. Extern Variable - exists outside of any function and available to all functions
5. Auto Variable - default class. Optional when declaring variable
6. Register Variable

# The 3 Data Types
## Basic Data Types  
1. **char:** Used to represent characters.
2. **int:** Used to represent integral numbers.
3. **float:** Used to represent decimal numbers up to 6-7 precision digits.
4. **double:** Used to represent decimal numbers up to 15 precision digits.
5. **void:** Used to represent the valueless entity.
![[Pasted image 20250902181705.png]]

## Derived Data Types
1. Arrays
2. Pointers

## User Defined Data Types
1. Structure
2. Union
3. Enumeration
4. typedefs

- Use `const` to prevent modification
- Use `static` inside functions to preserve state
- **Integer promotions**: Smaller integer types (`char`, `short`) get promoted to `int` or `unsigned int`.
## Printing

```c
int main()
{
    int roll_num;
    char name[50];
    scanf("Enter Roll No.: %d", &roll_num);     // taking input using scanf
    scanf("Enter Name: %s", name);
    printf("Name is %s and Roll Number is %d", name, roll_num);  // printing output using printf
    return 0;
}
```

|**Format Specifier**|**Description**|
|---|---|
|**%c**|For b type.|
|**%d**|For signed integer type.|
|**%f**|For float type.|
|**%lf**|Double|
|**%p**|Pointer|
|**%s**|String|
|**%u**|Unsigned int|
|**%%**|Prints % character|

|**Escape Sequence**|**Name**|**Description**|
|---|---|---|
|\b|Backspace|It is used to move the cursor backward.|
|\n|New Line|It moves the cursor to the start of the next line.|
|\r|Carriage Return|It moves the cursor to the start of the current line.|
|\t|Horizontal Tab|It inserts some whitespace to the left of the cursor and moves the cursor accordingly.|
|\v|Vertical Tab|It is used to insert vertical space.|
|\\|Backlash|Use to insert backslash character.|
|\”|Double Quote|It is used to display double quotation marks.|
|\0|NULL|It represents the NLL character.|
## Operators

Operators are the symbols that are used to perform some kind of operation. Operators can be classified based on the type of operation they perform.

These are the following types of operators in C:

|No.|Operator Type|Description|Example|
|---|---|---|---|
|**1.**|**Arithmetic Operators**|Operators that perform arithmetic operations.|+, -, *, /, %|
|**2.**|**Relational Operators**|They are used to compare two values.|<, >, <=, >=, ==, !=|
|**3.**|**Bitwise Operators**|They are used to perform bit-level operations on integers.|&, ^,|
|**4.**|**Logical Operators**|They perform logical operations such as logical AND, logical OR, etc.|&&,|
|**5.**|**Conditional Operators**|The conditional Operator is used to insert conditional code.|? :|
|**6.**|**Assignment Operators**|They are used to assign some value to the variables.|=, +=, -=, <<=|
|**7.**|**Miscellaneous Operators**|comma, addressof, sizeof, etc. are some other types of operators.|, sizeof, &, *, ->, .|
