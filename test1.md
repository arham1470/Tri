# Markdown Test & Syntax Showcase

Welcome to this sample Markdown document. You can use this file to test your Markdown renderers, previewers, or editors to ensure full formatting compatibility.

---

## 1. Text Formatting

Here are the basic inline formatting elements:

- **Bold text** using `**bold**` or `__bold__`
- *Italic text* using `*italic*` or `_italic_`
- ***Bold and italic*** using `***bold and italic***`
- ~~Strikethrough~~ using `~~strikethrough~~`
- Inline `code snippets` using backticks: `` `code` ``
- Subscript and superscript (renderer-dependent): H~2~O and X^2^
- Highlighted text (renderer-dependent): ==highlighted text==

---

## 2. Blockquotes

> "Simplicity is prerequisite for reliability."  
> — *Edsger W. Dijkstra*

Nested blockquote:
> First level of quoting.
>
> > Nested level of quoting with extra context.

---

## 3. Lists

### Unordered List
- Apples
  - Honeycrisp
  - Granny Smith
- Bananas
- Oranges

### Ordered List
1. Initialize the repository (`git init`)
2. Stage modified files (`git add .`)
3. Commit snapshot (`git commit -m "feat: initial commit"`)
4. Push to remote (`git push origin main`)

### Task / Checklist
- [x] Set up local development environment
- [x] Verify Git installation
- [ ] Write integration test suites
- [ ] Deploy to production

---

## 4. Code Blocks

### Python Example
```python
def fibonacci(n: int) -> list[int]:
    """Generate the first n Fibonacci numbers."""
    if n <= 0:
        return []
    sequence = [0, 1]
    while len(sequence) < n:
        sequence.append(sequence[-1] + sequence[-2])
    return sequence[:n]

if __name__ == "__main__":
    print(fibonacci(8))  # [0, 1, 1, 2, 3, 5, 8, 13]
```

### Shell / Bash Example
```bash
# Check installed Git version and path
git --version
which git
```

---

## 5. Tables

| Feature | Support | Compatibility | Notes |
| :--- | :---: | :---: | ---: |
| Headers | Yes | CommonMark | H1 through H6 |
| Syntax Highlighting | Yes | GFM | Requires language tag |
| Math (`LaTeX`) | Partial | MathJax / KaTeX | Often needs extensions |
| Tables | Yes | GFM | Standard alignment pipes |

---

## 6. Links and Images

- Link: [Official Git Website](https://git-scm.com)
- Reference-style Link: Check out [Google][google-link] for search.
- Image placeholder:

![Markdown Logo](https://markdown-here.com/img/icon256.png)

[google-link]: https://www.google.com

---

## 7. Mathematical Expressions (LaTeX)

Inline formula: $E = mc^2$ or $\lim_{x \to 0} \frac{\sin(x)}{x} = 1$

Block equation:
$$
f(x) = \int_{-\infty}^{\infty} \hat{f}(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$

---

## 8. Horizontal Rules

Three or more hyphens, asterisks, or underscores create a rule:

***

End of test markdown document.