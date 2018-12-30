---
title: Short Markdown and HTML reference
date: 2018-04-16
draft: false
categories: []
tags: ["HTML", "CSS", "Markdown"]
---
## Basic Markdown

### Headings

```
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```

Result:

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6


### Paragraphs

```
The Cosmos is all that is or ever was or ever will be. Our feeblest contemplations of the
Cosmos stir us — there is a tingling in the spine, a catch in the voice, a faint
sensation as if a distant memory, of falling from a height. We know we are
approaching the greatest of mysteries.
```
Result:

The Cosmos is all that is or ever was or ever will be. Our feeblest contemplations of the Cosmos stir us — there is a tingling in the spine, a catch in the voice, a faint sensation as if a distant memory, of falling from a height. We know we are approaching the greatest of mysteries.

### Formatting

#### Bold

```
I just love **bold text**.
```

Result:

I just love **bold text**.

#### Italic

```
The word *mountain* is in italic.
```

Result: 

The word *mountain* is in italic.

#### Verbatim

```
The assignment `my $name = 'Julia';` is in verbatim.
```

Result: 

The assignment `my $name = 'Julia';` is in verbatim.

### Lists

#### Ordered lists

```
1. First item
2. Second item
3. Third item
```

Result:

1. First item
2. Second item
3. Third item

#### Unordered lists

```
- First item
- Second item
- Third item
```

Result:

- First item
- Second item
- Third item



### Fenced code blocks

```markdown
    ```raku
    my $sum-of-squares = -> $a, $b { $a ** 2 + $b ** 2 }
    ```
```

Result: 

```raku
my $sum-of-squares = -> $a, $b { $a ** 2 + $b ** 2 }
```

### Horizontal Rules

```
***

---
___
```

Result:

***

---

---

### Links

```
https://duckduckgo.com

[DuckDuckGo](https://duckduckgo.com)
```

Result:

https://duckduckgo.com

[Duck Duck Go](https://duckduckgo.com)

### Images

```
![Gemini VI](https://c1.staticflickr.com/6/5607/31191744012_8c918c0d38_z.jpg)
```

Result: 

![Gemini VI](https://c1.staticflickr.com/6/5607/31191744012_8c918c0d38_z.jpg)

## Basic HTML Elements

### Blockquotes

The blockquote element represents content that is quoted from another source,
optionally with a citation which must be within a `footer` or `cite` element,
and optionally with in-line changes such as annotations and abbreviations.

```markdown
> To mix or not to mix HTML with Markdown? *That's the question*.
> <footer>- <cite>W. Shakespeare</cite></footer>
```

Result:

> To mix or not to mix HTML with Markdown? *That's the question*.
> <footer>- <cite>W. Shakespeare</cite></footer>

### Abbreviations

```
<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.
```

Result:

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

### Subscripts and superscripts

```
H<sub>2</sub>O
```
Result:

H<sub>2</sub>O

```
X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>
```
Result: 

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

### Keyboard input

```
Press <kbd>Yes</kbd> to continue. Or press <kbd>No</kbd> to exit.
```

Result:

Press <kbd>Yes</kbd> to continue. Or press <kbd>No</kbd> to exit.

### Mark text

```
Several species of <mark>salamander</mark> inhabit the temperate rainforest of the Pacific Northwest.
```

Result:

Several species of <mark>salamander</mark> inhabit the temperate rainforest of the Pacific Northwest.
