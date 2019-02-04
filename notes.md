1. An array is a set of consecutive memory locations used to store data.

2. C does not have a built-in string type; instead, strings are created out of characters arrays. '\0'(NUL) is used to indicate the end of a string.

3. Assign a string to a variable:

```c
char name[4] = "Sam";
```

```c
char name[4];
...
strcpy(name, "Sam");
...
```

4. Array initialized manner:

```c
int numbers[3] = {10, 972, 45};
```

```c
int numbers[] = {10, 972, 45};
```

```c
int numbers[3];

numbers[0] = 10;
numbers[1] = 972;
numbers[2] = 45;
```

5. Size of storage for int: short <= int <= long

6. A **break** statement inside a **switch** tells the computer to continue execution after the **switch**. If a **break** statement is not there, execution will continue with the next statement.

7. Local vars are temporary unless they are declared **static**.

8. The function type is not required by C. The type defaults to **int** if no function type is declared.

9. Function Prototype. A function prototype is simply the declaration of a function that specifies function's name, parameters and return type. It doesn't contain function body. A function prototype gives information to the compiler that the function may later be used in the program. The function prototype is not needed if the user-defined function is defined before the **main()** function.

10. All preprocessor commands begin with a hash mark(#) in column one.

11. The code to extract data from bit fields is relatively large and slow. Unless storage is a problem, **packed structures** should not be used.

12. Pointer Operators

| Operator | Meaning |
|:--------:|---------|
|`*`       | Dereference (given a pointer, get the thing referenced) |
|`&`       | Address of (given a thing, point to it) |

```c
int thing;
thing = 4;

int *thing_ptr;
thing_ptr = &thing
```

13. Special pointer `NULL`. It points nothing.

14. const Pointers

```c
const char *const title_ptr = "Title";
```
