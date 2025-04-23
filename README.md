The Norm

1. Naming Conventions
Prefix Rules
- Structures must start with s_
- Typedefs must start with t_
- Unions must start with u_
- Enumerations must start with e_
- Global variables must start with g_
Identifier Restrictions
- Identifiers (variables, functions, user-defined types) must:
  - Use only lowercase letters, digits, and underscores (snake_case)
  - Exclude capital letters
- File and directory names must follow the same snake_case convention
- Avoid non-standard ASCII characters (except within literal strings and characters)
Naming Principles
- All identifiers must be:
  - Explicit and meaningful
  - Readable in English
  - Separated by underscores
- Global variables must be const or static, unless explicitly permitted
Compilation Requirement
- Source files must compile successfully

2. Formatting Guidelines
Function and Line Constraints
- Maximum function length: 25 lines (excluding braces)
- Maximum line width: 80 columns (including comments)
- Tabulation: 4-character real tabs (ASCII 9)
Indentation and Spacing
- Indent code blocks within braces
- Braces standalone on their own line (except struct/enum/union declarations)
- No consecutive empty lines
- No trailing spaces or tabs
- No consecutive spaces
- Align variable names in their scope
- Pointer asterisks attached to variable names
Declaration Rules
- Declarations at function beginning
- One variable declaration per line
- Separate variable declarations from function body with an empty line
- No combined declaration and initialization (except globals, statics, constants)
Instruction and Control Structure Guidelines
- One instruction or control structure per line
- Allow line splitting with proper indentation
- Spaces around operators and after keywords
- Use braces for control structures (unless single-line exception)

3. Function Specifications
- Maximum 4 named parameters
- Explicitly prototype void-argument functions
- Name parameters in prototypes
- Maximum 5 variables per function
- Return statements in parentheses (except void returns)
- Single tab between return type and function name

4. Type Definitions
- Space after struct, enum, union, and typedef
- Consistent indentation for type names
- Structure declarations only in header files

5. Header File Rules
- Allowed contents: inclusions, declarations, defines, prototypes, macros
- Includes at file beginning
- Protect against multiple inclusions
- No inclusion of C files
- Justify header inclusions with comments

6. Macro and Preprocessor Guidelines
- Preprocessor constants for literal and constant values only
- No norm-bypassing or code obfuscation macros
- Uppercase macro names
- Preprocessor directives indented in conditional blocks
- Preprocessor instructions in global scope only

7. Forbidden Constructs
Prohibited language constructs:
- for loops
- do...while loops
- switch statements
- case labels
- goto statements
- Ternary operators
- Variable Length Arrays (VLAs)
- Implicit type declarations

8. Comment Guidelines
- No comments inside function bodies
- Comments at line end or on separate lines
- Write comments in English
- Comments should be meaningful and explanatory
- Avoid justifying poorly designed functions

9. File Limitations
- No .c file inclusions
- Maximum 5 function definitions per .c file
