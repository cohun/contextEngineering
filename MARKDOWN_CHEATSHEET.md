# Markdown Cheatsheet

A quick reference guide to the most common Markdown syntax.

## Headers

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Text Formatting

```markdown
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

***This text will be bold and italic***
___This will also be bold and italic___

~~This text will be struck through~~
```

## Blockquotes

You can create a blockquote by prefixing a line with `>`.

```markdown
> This is a blockquote.

> You can also have blockquotes that span multiple paragraphs.
>
> Just add a `>` on the blank lines between them.

> You can also nest blockquotes.
>> This is a nested blockquote.
```

## Lists

### Unordered Lists

Use `*`, `-`, or `+` for bullet points.

```markdown
* Item 1
* Item 2
  * Nested Item 2a
  * Nested Item 2b
- Item 3
```

### Ordered Lists

Use numbers followed by a period.

```markdown
1. First item
2. Second item
3. Third item
   1. Nested item
   2. Another nested item
```

## Code

### Inline Code

Wrap your code with single backticks (`` ` ``).

```markdown
Here is some `inline code`.
```

### Code Blocks

Wrap your code in triple backticks (```` ``` ````). You can also specify the language for syntax highlighting.

````markdown
```javascript
function helloWorld() {
  console.log("Hello, world!");
}
```
````

## Horizontal Rule

Create a horizontal rule with three or more hyphens, asterisks, or underscores.

```markdown
---
***
___
```

## Links

```markdown
[I'm an inline-style link](https://www.google.com)
[I'm an inline-style link with a title](https://www.google.com "Google's Homepage")
```

## Images

The syntax is similar to links, but with a `!` at the beginning.

```markdown
![alt text for the image](/path/to/your/image.jpg "Optional Title")
```

## Tables

```markdown
| Header 1 | Header 2 | Header 3 |
| :------- | :------: | -------: |
| Left-aligned | Centered | Right-aligned |
| Cell | Cell | Cell |
```

## Task Lists (GitHub Flavored Markdown)

```markdown
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

## Escaping Characters

To display a literal character that has special meaning in Markdown, use a backslash (`\`) in front of it.

```markdown
\*literal asterisks\*
```