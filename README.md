# regex (Cheat Sheet)

> [!NOTE]  
> This is a cheat sheet on regular expressions (mostly notes-to-self). They are incomplete by
> default.

### Example: Match the strings `\(` or `\)`.

Source: ChatGPT

```regex
\\\( | \\\)
```

In regex, since both the backslash (`\`) and the parentheses (`(` and `)`) are special characters,
you will need to escape them using double backslashes (`\\`).

- `\\\(`: This matches the string `\(`. The double backslashes `\\` escape the backslash itself in
  regex, and the `\(` escapes the opening parenthesis.
- `|`: This is the OR operator, meaning either the left-hand side or the right-hand side should
  match.
- `\\\)`: Similarly, this matches the string `\)`, where the first two backslashes escape the
  backslash, and the third backslash escapes the closing parenthesis.
