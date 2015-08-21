# Exercise 5: The Structure of a C Program
Let's learn some new commands!
Line by line:
- `include`: imports contents of one file into another
    - `*.h` - convention for 'header' files
    - a 'header' file contains lists of functions you want to use in your program
- `/* Multiline Comments */
- `// More comments`
- ```c
    int main(int argc, char *argv[])
  ```
  - computer loads your program and runs a function called `main`
  - funciton must return an `int` and take two parameters:
    - `int` for the argument count: `argc`
    - an array of ```char *``` strings
- open function body w/ `{`
    - beginning of a 'block'
        - `:` in Python
        - `do` or `{` in Ruby
- variable declaration and assignment:
    - `type name = value;`
- `printf` syntax:
    - `function_name(arg1, arg2)
- return from the main function
    - gives the OS your exit value
- close w/ `}`

