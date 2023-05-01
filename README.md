# CSC-4101-Prefix-Infix-Evaluator
This program converts prefix expressions to infix expressions and evaluates it. This program supports addition, subtraction, multiplication, and division.

| Prefix Expression | Infix Expression |
| ------------- | ------------- |
| + + A D * B C | A + D + (B * C) |
| * + A D * B C | (A + D) * (B * C) |
| + + + A B C D | A + B + C + D |

Below is an example of the program's output, provided a user's input is "\* + 3 5 + 19 6."

```
* + 3 5 + 19 6 --> (3 + 5) * (19 + 6) = 200
```
