| Type | Description |
|---|---|
| int | Whole numbers |
| float | Decimal numbers |
| double | More precise decimal numbers |
| char | Single character |
| bool | True or false |
| void | No value |

| Format Specifier | Description |               
|---|---|
| `%d`| Signed integer |
| `%u` | Unsigned integer |
| `%o` | Octal integer |
| `%x` | Hexadecimal (lowercase) |
| `%X` | Hexadecimal (uppercase) |
| `%f` | Floating-point number |
| `%e` | Scientific notation |
| `%c` | Single character |
| `%s` | String |
| `%ld` | Long integer |

| Function | Description |
|---|---|
| `scanf()` | Reads formatted input from the user. |
| `printf()` | Displays formatted output on the screen. |
| `getchar()` | Reads a single character from the user. |
| `putchar()` | Displays a single character on the screen. |
| `fgets()` | Reads a line of text, including spaces. |
| `puts()` | Displays a string followed by a new line. |

| Escape Sequence | Use |
|---|---|
| \n | Moves to a new line |
| \t | Gives a tab space |
| \\ | Prints a backslash |
| \" | Prints double quotes |
| \' | Prints single quote |

### 5. Precision

Precision is used to control the number of digits shown after the decimal point.

For example:
`printf("%.2f", 12.3456);`

Output:
`12.35`
