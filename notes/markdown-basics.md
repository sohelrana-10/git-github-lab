# Main Title

## Markdown for GitHub

## 1. Introduction

I am going to learn about Markdown files.

I am learning Markdown because GitHub recommends using a clear `README.md` file and a `LICENSE` file for each repository, where appropriate.

## 2. Headings

Markdown supports six levels of headings.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## 3. Text Formatting

### Bold

```markdown
**This is bold text.**
```

**This is bold text.**

### Italic

```markdown
*This is italic text.*
```

*This is italic text.*

### Bold and Italic

```markdown
***This is bold and italic text.***
```

***This is bold and italic text.***

### Strikethrough

```markdown
~~This is strikethrough text.~~
```

~~This is strikethrough text.~~

### Subscript

GitHub supports HTML tags for subscript formatting.

```html
H<sub>2</sub>O
```

H\<sub>2\</sub>O

### Superscript

```html
X<sup>2</sup> + Y<sup>2</sup>
```

X\<sup>2\</sup> + Y\<sup>2\</sup>

### Highlight

GitHub supports the HTML `<mark>` tag.

```html
<mark>This text is highlighted.</mark>
```

<mark>This text is highlighted.</mark>

## 4. Line Breaks and Paragraphs

### New Paragraph

Leave a blank line between paragraphs.

```markdown
This is the first paragraph.

This is the second paragraph.
```

### Line Break

Add two trailing spaces at the end of a line, or use the HTML `<br>` tag.

```markdown
This is the first line.  
This is the second line.
```

Alternatively:

```html
This is the first line.<br>
This is the second line.
```

## 5. Lists

### Unordered List

Use `-`, `*`, or `+` to create an unordered list.

```markdown
- Python
- SQL
- Git
- GitHub
```

- Python
- SQL
- Git
- GitHub

### Ordered List

Use numbers followed by periods.

```markdown
1. Learn Python
2. Learn SQL
3. Learn Git
4. Learn GitHub
```

1. Learn Python
2. Learn SQL
3. Learn Git
4. Learn GitHub

### Nested List

Indent nested items with spaces.

```markdown
- Programming
  - Python
  - Java
- Databases
  - SQLite
  - PostgreSQL
```

- Programming
  - Python
  - Java
- Databases
  - SQLite
  - PostgreSQL

### Task List

Use `- [ ]` for incomplete tasks and `- [x]` for completed tasks.

```markdown
- [x] Learn Markdown headings
- [x] Learn text formatting
- [ ] Learn Markdown tables
- [ ] Practice Git commands
```

- [x] Learn Markdown headings
- [x] Learn text formatting
- [ ] Learn Markdown tables
- [ ] Practice Git commands

## 6. Links

### External Link

```markdown
[Visit GitHub](https://github.com)
```

[Visit GitHub](https://github.com)

### Link to Another File in the Repository

```markdown
[Read the License](LICENSE)
```

### Link to a Section

```markdown
[Go to Text Formatting](#3-text-formatting)
```

[Go to Text Formatting](#3-text-formatting)

## 7. Images

Use the following syntax to display an image.

```markdown
![Description of image](images/example.png)
```

- `!` indicates an image.
- `[Description of image]` provides alternative text.
- `(images/example.png)` specifies the image path.

## 8. Code Formatting

### Inline Code

Use single backticks for a short piece of code.

```markdown
Use `print()` to display output in Python.
```

Use `print()` to display output in Python.

### Code Block

Use three backticks before and after a block of code.

````markdown
```python
name = "Sohel"
print(name)
```
````

Example output:

```python
name = "Sohel"
print(name)
```

### Code Block Without a Language

````markdown
```
This is a plain code block.
```
````

## 9. Blockquotes

Use `>` to create a blockquote.

```markdown
> This is a blockquote.
```

> This is a blockquote.

### Nested Blockquote

```markdown
> This is the first level.
>
> > This is the second level.
```

> This is the first level.
>
> > This is the second level.

## 10. Horizontal Rule

Use three or more hyphens, asterisks, or underscores.

```markdown
---
```

Example:

---

## 11. Tables

Use pipes (`|`) to separate columns and hyphens (`-`) to create the header separator.

```markdown
| Language | Purpose |
| --- | --- |
| Python | Programming |
| SQL | Database queries |
| Markdown | Documentation |
```

| Language | Purpose          |
| -------- | ---------------- |
| Python   | Programming      |
| SQL      | Database queries |
| Markdown | Documentation    |

### Align Table Columns

```markdown
| Left | Center | Right |
| :--- | :---: | ---: |
| A | B | C |
| D | E | F |
```

| Left | Center | Right |
| :--- | :----: | ----: |
| A    |    B   |     C |
| D    |    E   |     F |

## 12. Escaping Special Characters

Use a backslash (`\`) before a Markdown character when you want to display it literally.

```markdown
\*This text will not be italicized.\*
\# This will not be a heading.
```

Examples:

\*This text will not be italicized.\*

\# This will not be a heading.

## 13. Mathematical Expressions

GitHub supports mathematical expressions using LaTeX syntax.

### Inline Math

```markdown
The equation is $x^2 + y^2 = z^2$.
```

The equation is $(x^2 + y^2 = z^2)$.

### Block Math

```markdown
$$
a^2 + b^2 = c^2
$$
```

$$
a^2 + b^2 = c^2
$$

## 14. Emojis

GitHub supports emoji shortcodes.

```markdown
:smile: :rocket: :white_check_mark:
```

Examples: :smile: :rocket: :white_check_mark:

## 15. Collapsible Sections

Use HTML `<details>` and `<summary>` tags to create a collapsible section.

```html
<details>
  <summary>Click to expand</summary>

  This content is hidden until expanded.

</details>
```

<details>
<summary>Click to expand</summary>

This content is hidden until expanded.

</details>

## 16. Important Notes

- Markdown files commonly use the `.md` extension.
- `README.md` explains what a repository contains and how to use it.
- `LICENSE` specifies the terms under which others may use the project.
- GitHub Flavored Markdown (GFM) adds features such as task lists, tables, and strikethrough.
- Some HTML tags work in GitHub Markdown, but not every HTML tag or attribute is supported.
- Always preview your Markdown file on GitHub to confirm that it renders correctly.

