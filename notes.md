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
