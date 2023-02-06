# Markdown

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
	- [Internal Links](#1-internal-links)
	- [External Links](#2-external-links)
- [Images](#images)
	- [Inline Style](#1-inline-style)
	- [Custom HTML embedding](#2-custom-html-embedding)
- [Code Blocks & Syntax Highlighting](#code-blocks--syntax-highlighting)
	- [Code Blocks](#1-code-blocks)
	- [Inline Code](#2-inline-code)
- [Keyboard Entries](#keyboard-entries)
- [Tables](#tables)
- [Blockquotes](#blockquotes)
- [Inline HTML](#inline-html)
- [Tex Mathematical Expressions](#tex-mathematical-expressions)
- [Footnotes](#footnotes)
- [Diagramming](#diagrams)
	- [Mermaid Diagrams](#1-mermaid-diagrams)
	- [GeoJSON and TopoJSON maps](#2-geojson-and-topojson-maps)
	- [STL 3D models](#3-stl-3d-models)
- [References](#references)
- [License](#license)

## Headers
- **Headers** serve as hierarchy differentiators, just as in any typical word processor. 

#### **_Syntax_**
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

#### **_Example_**
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Horizontal Rule
- **Horizontal rules** can be implemented for dividing sections.

#### **_Syntax_**
```
Use 3 or more of the following characters: 

Hyphens: ---
Asterisks: ***
Underscores: ___
```

#### **_Example_**
---
Hyphens
***
Asterisks
___
Underscores

## Emphasis
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

##### **Example**
_Italics_
**Bold**
**_Combined_**
~~Strikethrough~~
==Highlight==

## Line Breaks
- **Line breaks** are used to separate text.

##### **Code**
```
Single Line Break:

Double Line Break:


```

##### **Example**
Single Line Break:

Double Line Break:


## Lists
- **Lists** are used to denote a number of connected items or names written or printed consecutively.
- Lists can be _ordered_ or _unordered_.
- Upon inputting the first number in ordered lists or the first bullet in unordered lists and inputting a `newline`, text editors will continue with sequence. 

### 1. Ordered Lists

##### **Code**
```
Ordered list:
1. Item 1
2. Item 2
3. Item 3
4. Item 4
5. Item n
```

##### **Example**
1. Item 1
2. Item 2
3. Item 3
4. Item 4
5. Item n

### 2. Unordered Lists

##### **Code**
```
- Item 1
- Item 2
- Item 3
- Item 4
- Item n
```

##### **Example**
- Item 1
- Item 2
- Item 3
- Item 4
- Item n

## Task Lists
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

##### **Example**
[x] Task 1
[x] Task 2
[ ] Task n

## Links
- **Links** can be inserted by using squre brackets `[]` and parenthesis `()`.  
- Links can be external (i.e. some external website) or internal (i.e. inside same Markdown document).

### 1. External Link

##### **Code**
```
[Google](https://www.google.com)
```

##### Example
[Google](https://www.google.com)

### 2. Internal Link

##### **Code**
```
[Table of Contents](#0-table-of-contents)
```

##### **Example**
[Table of Contents](#0-table-of-contents)

## Images
- **Images** can be embedded inline by using default Markdown syntax.
- **Images** can also be custom embedded using HTML syntax.

### 1. Inline Style

##### **Code**
```
Inline-style: 
![alt text](https://raw.githubusercontent.com/pabloagn/digital-assets/master/markdown-cheatsheet-asset-1.jpg "Digital Asset Inline")
```

##### **Example**
![alt text](https://raw.githubusercontent.com/pabloagn/digital-assets/master/markdown-cheatsheet-asset-1.jpg "Digital Asset 1")

### 2. Custom HTML embedding

##### **Code**
```
<div><img src="https://raw.githubusercontent.com/pabloagn/digital-assets/master/markdown-cheatsheet-asset-1.jpg" alt="Example"/></div>

Some text describing the image
```

##### **Example**
<div><img src="https://raw.githubusercontent.com/pabloagn/digital-assets/master/markdown-cheatsheet-asset-1.jpg" alt="Example"/></div>

We just need to be sure to include any text below the image after a newline.

## Code Blocks & Syntax Highlighting
- **Code blocks** are used to denote fragments of code, in an easy-to-copy fashion.
- _Highlighting_ is language dependent and must be specified in block.

### 1. Code Blocks & Syntax Highlighting
- A code block must be written inside three back-ticks ` ``` `, or must be indented with four spaces.
- If language is left unspecified, highlighting won't appear.

##### **Code**
- Unhighlighted
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

- Highlighted
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

##### **Example**
- Unhighlighted
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

- Highlighted
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

### 2. Inline Code
- A code segment between text can be specified by wrapping code in single back-ticks ` `` `.

##### **Code**
```
A Python `class` serves as blueprint for creating `objects`.
```

##### **Example**
A Python `class` serves as a blueprint for creating `objects`.

## Keyboard Entries
- **Keyboard entries** are a way to represent actual keys in a keyboard, using a special format.
- By default, Markdown does not support this type of formatting, but we can achieve this by using HTML code.
- Similar to code blocks, we can symbolize keyboard entries by using the HTML `<kbd></kbd>` element.

##### **Code**
```
To execute, press the <kbd>Enter</kbd> key.
```

##### **Example**
To execute, press the <kbd>Enter</kbd> key.

## Tables
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

##### **Example**
| Header 1 | Header 2 | Header n |
|---|---|---|
| r1c1 | r1c2 | r1cn |
| r2c1 | r2c2 | r2cn |

## Blockquotes
- **Blockquotes** are used to indicate the quotation of a large section of text from another source.

##### **Code**
```
> Blockquotes are used in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
```

##### **Example**
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

## Inline HTML
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

##### **Example**
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

## Tex Mathematical Expressions
- **Tex** mathematical expressions can be declared in Markdown by using Tex syntax directly.
- To enter a Tex expression, wrap in dollar signs `$`.

##### **Code**
```
$f_X(x)={k \over \sqrt{2\pi\sigma^2}}e^{{-({x-\mu})^2}\over2\sigma^2}, x \geq 0$
```

##### **Example**
$f_X(x)={k \over \sqrt{2\pi\sigma^2}}e^{{-({x-\mu})^2}\over2\sigma^2}, x \geq 0$

## Footnotes
- **Footnotes** can be added by enclosing any keyword in squared brackets and ading the caret symbol before keyword `[^footnote_1]`.
- Upn clicking the footnote, the reference will highlight.
- Note that in **Obsidian** at least, footnotes are rendered until _read-mode_ is accessed.

##### **Code**
```
This is the text that will contain a footnote.[^footnote_1]

We will later reference the footnote by denoting as follows:

[^footnote]: This is the actual reference.
```

##### **Example**
This is a sentence with footnote. [^footnote]

 [^footnote]: This is the actual footnote.

## Diagramming

### 1. Mermaid Diagrams

### 2. GeoJSON and TopoJSON maps

### 3. STL 3D models

## References
- [ChristianLempa/cheat-sheets/misc/markdown.md](https://github.com/ChristianLempa/cheat-sheets/blob/main/misc/markdown.md)
- [adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [normal-distribution-density-function](https://en.wikipedia.org/wiki/Normal_distribution)

## License
This content is protected under the [GNU Free Documentation License v1.3](https://github.com/pabloagn/documentation/blob/master/LICENSE).