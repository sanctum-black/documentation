<article class="first">
  <div class="title">
    <h1>Markdown</h1>
  </div>
</article>

---

[![made-with badge](https://img.shields.io/static/v1?label=Made%20with&message=Obsidian&color=7d5bed&logo=obsidian&labelColor=1a1a1a&style=flat)](https://obsidian.md/)

[![type](https://img.shields.io/static/v1?label=Type&message=documentation&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAi0lEQVRIS+2WMQ7AIAhF/UNXrtP7rz2OYxeqTWxMTBUSxQVXfnzyQQKC8YExL7zAGCNbgIkIsIKVhBw4vbR7unR6Gp0LvwxXd2v+EvkdDpxWXpWlRTyi9/pABRyBJHEHSlxSadxSlV0SsVsqcUml2W/pynWxnsXNisHMRxrCl8qvH3ECnQDuOmy+0zwB4WNxmUKgwwAAAABJRU5ErkJggg==&labelColor=1a1a1a&style=flat)](https://pabloagn.com/documentation/) [![category](https://img.shields.io/static/v1?label=Category&message=writing-and-formatting&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAB9UlEQVRIS6VWMU7DQBDkDAQEdrAoCISCAomCL1DxC95Azy9oeQS/oOIHVFAgREFoCHGCRSzZzEU+63LZ9W6CO/vudmZ2d9Zn1pTPaDSqut2usduHw+FpFEUv7t1fk8LNAkiPDWj3+ADuTPjNvXMxWwGzLCuqqtqwh5MkiY0xEwfOAfrEKFAWUBO4DZQDXgCEqjuouvbZUanUrocpngMMVUkKtKC+WhFQUudAUd8r1PkepJ/w7Tysn4uzkNJlascF9WOASAki6w0xrn19b3Gpps5y3kRfJADPZgr9gJSP0EgDHDiQ/Mp50PfxAmDtuQhsZmb/z0OVhwSkmGrSGp5bGRDp3EFaJ5JaiahdZ2vYNj/JkWVMgW7sgNw2yOW+99gacp7TeFE72OcUrgo4Ho93+/3+D5T9QmGHm0BNSnHgMI7jj9Ai2tElZGCK9S3S+GA4BcNNydBaIuEstu/iLJWCa+pLDm+Nz+xQAsBenucnRVG8asFq0s/Yf9YoVAI21wyn3N4I7M1A8ijWHwB42XrFqIO9YfMRlVqqyXC5ukED3nIEVJcoBXv1lmWa5gIpeeQioyTWVj1uXf0DpgKUZbmfpunXKnVnU9rWDKiTHRSDNkDu36iqIQK/Q+mxU8sBYniL/1EVoJ9Wqwo/5x6Cf9YKv6Em1XbNH5bGfSwvuRe1AAAAAElFTkSuQmCC&labelColor=1a1a1a&style=flat)](https://pabloagn.com/categories/writing-and-formatting/) [![technologies](https://img.shields.io/static/v1?label=Technologies&message=Markdown,HTML,LaTeX&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAACXBIWXMAAAsTAAALEwEAmpwYAAAA1klEQVR4nM2RMW7CUBBEnUikIQUIlBJxrrQgJG7ABRBnoUkaWhpoUgWJlgNYbvz/G1dUi1ayoy87rpOtVrszs6OdLPtXlef5UNJXjHHcCwohjMzsKZ3FGN+Bq/e+c0xHGfiWtEznkg6SNnW/dIxjs0YJ2AMnM3tJSFPgHkKY17gBcAQ+zOw5A3aSbsCkdW0NnNOZY2rstpcInJ3cS/SzwGdqtSzLmdusquqtIXWsehVF8QpcJK1qmxt/TMv6wjE/z0leP27i8Ag8inT/axxtAQ+9o/zn9QD3JOiyTjnQEQAAAABJRU5ErkJggg==&labelColor=1a1a1a&style=flat)](https://pabloagn.com/technologies/)

**Markdown** is a lightweight markup language for creating formatted text using a plain-text editor. 

Extensions used are `.md` and `.markdown`.

## Table of Contents
- [Headers](#headers)
- [Horizontal Rule](#horizontal-rule)
- [Emphasis](#emphasis)
- [Line Breaks](#line-breaks)
- [Lists](#lists)
	- [Ordered Lists](#1-ordered-lists)
	- [Unordered Lists](#2-unordered-lists)
- [Task Lists](#task-lists)
- [Links](#links)
	- [External Links](#1-external-links)
	- [Internal Links](#2-internal-links)
- [Images](#images)
	- [Inline Style](#1-inline-style)
	- [Custom HTML embedding](#2-custom-html-embedding)
- [Code Blocks & Syntax Highlighting](#code-blocks--syntax-highlighting)
	- [Code Blocks](#1-code-blocks)
		- [Unhlighlighted](#11-unhighlighted)
		- [Highlighted](#12-highlighted)
	- [Inline Code](#2-inline-code)
- [Keyboard Entries](#keyboard-entries)
- [Tables](#tables)
- [Blockquotes](#blockquotes)
- [Inline HTML](#inline-html)
- [Tex Mathematical Expressions](#tex-mathematical-expressions)
- [Footnotes](#footnotes)
- [Diagramming](#diagramming)
	- [Mermaid Diagrams](#1-mermaid-diagrams)
	- [GeoJSON and TopoJSON maps](#2-geojson-and-topojson-maps)
	- [STL 3D models](#3-stl-3d-models)
- [References](#references)
- [License](#license)
- [Copyright](#copyright)

# Headers
- **Headers** serve as hierarchy differentiators, just as in any typical word processor. 

##### **Code**
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

##### **Output**
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Horizontal Rule
- **Horizontal rules** can be implemented for dividing sections.

##### **Code**
```
Use 3 or more of the following characters: 

Hyphens: ---
Asterisks: ***
Underscores: ___
```

##### **Output**
---
Hyphens
***
Asterisks
___
Underscores

---
# Emphasis
- **Emphasis** characters are used to provide weight, to differentiate, to denote a word in another language, or to denote a keyword, among other applications.

##### **Code**
```
Italics: *with asterisks* or _with underscores_.
Bold: **with double asterisks**.
Combined: **with double asterisks _and underscores_**
Strikethrough: ~~with two tildes~~.
Highlight: ==with dpuble equal signs==.
Underlined: Not possible in Markdown.
```

##### **Output**
_Italics_
**Bold**
**_Combined_**
~~Strikethrough~~
==Highlight==

---
# Line Breaks
- **Line breaks** are used to separate text.

##### **Code**
```
Single Line Break:

Double Line Break:


```

##### **Output**
Single Line Break:

Double Line Break:


---

# Lists
- **Lists** are used to denote a number of connected items or names written or printed consecutively.
- Lists can be _ordered_ or _unordered_.
- Upon inputting the first number in ordered lists or the first bullet in unordered lists and inputting a `newline`, text editors will continue with sequence. 

## 1. Ordered Lists

##### **Code**
```
Ordered list:
1. Item 1
2. Item 2
3. Item 3
4. Item 4
5. Item n
```

##### **Output**
1. Item 1
2. Item 2
3. Item 3
4. Item 4
5. Item n

## 2. Unordered Lists

##### **Code**
```
- Item 1
- Item 2
- Item 3
- Item 4
- Item n
```

##### **Output**
- Item 1
- Item 2
- Item 3
- Item 4
- Item n

---

# Task Lists
- A **Task List** is used to graphically represent a checklist. 
- A Task List has two components:
	- Check: Use square brackets `[]`. Fill with `x` if checked, otherwise empty.
	- Task: The actual task to denote.

##### **Code**
```
[x] Task 1
[x] Task 2
[ ] Task n
```

##### **Output**
[x] Task 1
[x] Task 2
[ ] Task n

---

# Links
- **Links** can be inserted by using squre brackets `[]` and parenthesis `()`.  
- Links can be external (i.e. some external website) or internal (i.e. inside same Markdown document).

## 1. External Links

##### **Code**
```
[Google](https://www.google.com)
```

##### **Output**
[Google](https://www.google.com)

## 2. Internal Links

##### **Code**
```
[Table of Contents](#0-table-of-contents)
```

##### **Output**
[Table of Contents](#0-table-of-contents)

---

# Images
- **Images** can be embedded inline by using default Markdown syntax.
- **Images** can also be custom embedded using HTML syntax.

## 1. Inline Style

##### **Code**
```
Inline-style: 
![alt text](https://raw.githubusercontent.com/pabloagn/digital-assets/master/markdown-cheatsheet-asset-1.jpg "Digital Asset Inline")
```

##### **Output**
![alt text](https://pabloagn.com/wp-content/uploads/2023/04/markdown-cheatsheet-asset-1.jpg "Digital Asset 1")

## 2. Custom HTML embedding

##### **Code**
```
<div><img src="https://raw.githubusercontent.com/pabloagn/digital-assets/master/markdown-cheatsheet-asset-1.jpg" alt="Example"/></div>

Some text describing the image
```

##### **Output**
<div><img src="https://pabloagn.com/wp-content/uploads/2023/04/markdown-cheatsheet-asset-1.jpg" alt="Example"/></div>

We just need to be sure to include any text below the image after a newline.

---
# Code Blocks & Syntax Highlighting
- **Code blocks** are used to denote fragments of code, in an easy-to-copy fashion.
- _Highlighting_ is language dependent and must be specified in block.

## 1. Code Blocks
- A code block must be written inside three back-ticks ` ``` `, or must be indented with four spaces.
- If language is left unspecified, highlighting won't appear.

### 1.1 Unhighlighted

##### **Code**
````
```
def myFun():
	l = []
	for i in range(2):
		a = i**2
		l.append(a)
		print(a)
	return l

myFun()
```
````

##### **Output**
```
def myFun():
	l = []
	for i in range(2):
		a = i**2
		l.append(a)
		print(a)
	return l

myFun()
```

### 1.2 Highlighted

##### **Code**
````
```python
def myFun():
	l = []
	for i in range(2):
		a = i**2
		l.append(a)
		print(a)
	return l

myFun()
```
````

##### **Output**
```python
def myFun():
	l = []
	for i in range(2):
		a = i**2
		l.append(a)
		print(a)
	return l

myFun()
```

## 2. Inline Code
- A code segment between text can be specified by wrapping code in single back-ticks ` `` `.

##### **Code**
```
A Python `class` serves as blueprint for creating `objects`.
```

##### **Output**
A Python `class` serves as a blueprint for creating `objects`.

---

# Keyboard Entries
- **Keyboard entries** are a way to represent actual keys in a keyboard, using a special format.
- By default, Markdown does not support this type of formatting, but we can achieve this by using HTML code.
- Similar to code blocks, we can symbolize keyboard entries by using the HTML `<kbd></kbd>` element.

##### **Code**
```
To execute, press the <kbd>Enter</kbd> key.
```

##### **Output**
To execute, press the <kbd>Enter</kbd> key.

---

# Tables
- **Tables** can be used to structure data, and are comprised of headers and body.
- A table is denoted by specifying headers first, separator second, and body third.
- Outer pipes (|) are optional.

##### **Code**
```
| Header 1 | Header 2 | Header n |
|---|---|---|
| r1c1 | r1c2 | r1cn |
| r2c1 | r2c2 | r2cn |
```

##### **Output**
| Header 1 | Header 2 | Header n |
|---|---|---|
| r1c1 | r1c2 | r1cn |
| r2c1 | r2c2 | r2cn |

---

# Blockquotes
- **Blockquotes** are used to indicate the quotation of a large section of text from another source.

##### **Code**
```
> Blockquotes are used in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
```

##### **Output**
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

---

# Inline HTML
- Raw **HTML** can be included in Markdown.

##### **Code**
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```

##### **Output**
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

---

# Tex Mathematical Expressions
- **Tex** mathematical expressions can be declared in Markdown by using Tex syntax directly.
- To enter a Tex expression, wrap in dollar signs `$`.

##### **Code**
```
$f_X(x)={k \over \sqrt{2\pi\sigma^2}}e^{{-({x-\mu})^2}\over2\sigma^2}, x \geq 0$
```

##### **Output**
$f_X(x)={k \over \sqrt{2\pi\sigma^2}}e^{{-({x-\mu})^2}\over2\sigma^2}, x \geq 0$

---

# Footnotes
- **Footnotes** can be added by enclosing any keyword in squared brackets and ading the caret symbol before keyword `[^footnote_1]`.
- Upn clicking the footnote, the reference will highlight.
- Note that in **Obsidian** at least, footnotes are rendered until _read-mode_ is accessed.

##### **Code**
```
This is the text that will contain a footnote.[^footnote_1]

We will later reference the footnote by denoting as follows:

[^footnote]: This is the actual reference.
```

##### **Output**
This is a sentence with footnote. [^footnote]

 [^footnote]: This is the actual footnote.

---

# Diagramming

## 1. Mermaid Diagrams

## 2. GeoJSON and TopoJSON maps

## 3. STL 3D models

---

# References
- [ChristianLempa/cheat-sheets/misc/markdown.md](https://github.com/ChristianLempa/cheat-sheets/blob/main/misc/markdown.md)
- [adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [normal-distribution-density-function](https://en.wikipedia.org/wiki/Normal_distribution)

---

# Copyright
Pablo Aguirre, GNU Free Documentation License v1.3, All Rights Reserved.