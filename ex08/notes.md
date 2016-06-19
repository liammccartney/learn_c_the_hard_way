## Arrays
There are a 'huge' number of ways to create areas
Example Syntax:
```c
//type name[] = {initializer}
int areas[] {10, 12, 13, 14, 20}
```
"I want an array of type that is initialized to {...}:
What C Does:
    - Look at the type, in this case `int`
    - Look at the `[]` and see that there is no length given
    - Look at the initialized, `{10, 12, 13, 14, 20}` and figure out that those are the 5 ints you want in your array
    - Create a piece of memory in the computer to hold 5 integers, one after the other
    - Take the name, `areas`, and assign it this location
