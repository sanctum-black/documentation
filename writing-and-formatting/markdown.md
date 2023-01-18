# Markdown
**Markdown** is a lightweight markup language for creating formatted text using a plain-text editor. 

Extensions used are `.md` and `.markdown`.

## Table of Contents
1. [Headers](#1-headers)
2. [Horizontal Rule](#2-horizontal-rule)
3. [Emphasis](#3-emphasis)
4. [Line Breaks](#4-line-breaks)
5. [Lists](#5-lists)
	1. [Ordered Lists](#i-ordered-lists)
	2. [Unordered Lists](#ii-unordered-lists)
6. [Task Lists](#6-task-lists)
7. [Links](#7-links)
	1. [Internal Links](#i-internal-links)
	2. [External Links](#ii-external-links)
8. [Images](#8-images)
9. [Code Blocks & Syntax Highlighting](#9-code-blocks--syntax-highlighting)
	1. [Code Blocks](#i-code-blocks)
	2. [Inline Code](#ii-inline-code)
10. [Keyboard Entries](#10-keyboard-entries)
11. [Tables](#11-tables)
12. [Blockquotes](#12-blockquotes)
13. [Inline HTML](#13-inline-html)
14. [Tex Mathematical Expressions](#14-tex-mathematical-expressions)
15. [Footnotes](#15-footnotes)
16. [References](#16-references)

## 1. Headers
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

## 2. Horizontal Rule
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

## 3. Emphasis
- **Emphasis** characters are used to provide weight, to differentiate, to denote a word in another language, or to denote a keyword, among other applications.

### **_Syntax_**
```
Italics: *with asterisks* or _with underscores_.
Bold: **with double asterisks**.
Combined: **with double asterisks _and underscores_**
Strikethrough: ~~with two tildes~~.
Highlight: ==with dpuble equal signs==.
Underlined: Not possible in Markdown.
```

### **_Example_**
_Italics_
**Bold**
**_Combined_**
~~Strikethrough~~
==Highlight==

## 4. Line Breaks
- **Line breaks** are used to separate text.

### **_Syntax_**
```
Single Line Break:

Double Line Break:


```

### **_Example_**
Single Line Break:

Double Line Break:


## 5. Lists
- **Lists** are used to denote a number of connected items or names written or printed consecutively.
- Lists can be _ordered_ or _unordered_.
- Upon inputting the first number in ordered lists or the first bullet in unordered lists and inputting a `newline`, text editors will continue with sequence. 

### i. Ordered Lists

### **_Syntax_**
```
Ordered list:
1. Item 1
2. Item 2
3. Item 3
4. Item 4
5. Item n
```

### **_Example_**
1. Item 1
2. Item 2
3. Item 3
4. Item 4
5. Item n

### ii. Unordered Lists

### **_Syntax_**
```
- Item 1
- Item 2
- Item 3
- Item 4
- Item n
```

### **_Example_**
- Item 1
- Item 2
- Item 3
- Item 4
- Item n

## 6. Task Lists
- A **Task List** is used to graphically represent a checklist. 
- A Task List has two components:
	- Check: Use square brackets `[]`. Fill with `x` if checked, otherwise empty.
	- Task: The actual task to denote.

### **_Syntax_**
```
[x] Task 1
[x] Task 2
[ ] Task n
```

### **_Example_**
[x] Task 1
[x] Task 2
[ ] Task n

## 7. Links
- **Links** can be inserted by using squre brackets `[]` and parenthesis `()`.  
- Links can be external (i.e. some external website) or internal (i.e. inside same Markdown document).

### i. External Link

### **_Syntax_**
```
[Google](https://www.google.com)
```

### **_Example_**
[Google](https://www.google.com)

### ii. Internal Link

### **_Syntax_**
```
[Table of Contents](#0-table-of-contents)
```

### **_Example_**
[Table of Contents](#0-table-of-contents)

## 8. Images
- **Images** can be embedded inline.

### **_Syntax_**
```
Inline-style: 
![alt text](https://raw.githubusercontent.com/pabloaguirrenck/digital-assets/master/markdown-cheatsheet-asset-1.jpg "Digital Asset Inline")
```

### **_Example_**
- Inline-style: 
![alt text](https://raw.githubusercontent.com/pabloaguirrenck/digital-assets/master/markdown-cheatsheet-asset-1.jpg "Digital Asset 1")

## 9. Code Blocks & Syntax Highlighting
- **Code blocks** are used to denote fragments of code, in an easy-to-copy fashion.
- _Highlighting_ is language dependent and must be specified in block.

### i. Code Blocks & Syntax Highlighting
- A code block must be written inside three back-ticks ` ``` `, or must be indented with four spaces.
- If language is left unspecified, highlighting won't appear.

### **_Syntax_**
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

### **_Example_**
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

### ii. Inline Code
- A code segment between text can be specified by wrapping code in single back-ticks ` `` `.

### **_Syntax_**
```
A Python `class` serves as blueprint for creating `objects`.
```

### **_Example_**
A Python `class` serves as a blueprint for creating `objects`.

## 10. Keyboard Entries
- **Keyboard entries** are a way to represent actual keys in a keyboard, using a special format.
- By default, Markdown does not support this type of formatting, but we can achieve this by using HTML code.
- Similar to code blocks, we can symbolize keyboard entries by using the HTML `<kbd></kbd>` element.

### **_Syntax_**
```
To execute, press the <kbd>Enter</kbd> key.
```

### _Example_
To execute, press the <kbd>Enter</kbd> key.

## 11. Tables
- **Tables** can be used to structure data, and are comprised of headers and body.
- A table is denoted by specifying headers first, separator second, and body third.
- Outer pipes (|) are optional.

### **_Syntax_**
```
| Header 1 | Header 2 | Header n |
|---|---|---|
| r1c1 | r1c2 | r1cn |
| r2c1 | r2c2 | r2cn |
```

### **_Example_**
| Header 1 | Header 2 | Header n |
|---|---|---|
| r1c1 | r1c2 | r1cn |
| r2c1 | r2c2 | r2cn |

## 12. Blockquotes
- **Blockquotes** are used to indicate the quotation of a large section of text from another source.

### **_Syntax_**
```
> Blockquotes are used in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
```

### **_Example_**
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

## 13. Inline HTML
- Raw **HTML** can be included in Markdown.

### **_Syntax_**
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```

### **_Example_**
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

## 14. Tex Mathematical Expressions
- **Tex** mathematical expressions can be declared in Markdown by using Tex syntax directly.
- To enter a Tex expression, wrap in dollar signs `$`.

### **_Syntax_**
```
$f_X(x)={k \over \sqrt{2\pi\sigma^2}}e^{{-({x-\mu})^2}\over2\sigma^2}, x \geq 0$
```

### **_Example_**
$f_X(x)={k \over \sqrt{2\pi\sigma^2}}e^{{-({x-\mu})^2}\over2\sigma^2}, x \geq 0$

## 15. Footnotes
- **Footnotes** can be added by enclosing any keyword in squared brackets and ading the caret symbol before keyword `[^footnote_1]`.
- Upn clicking the footnote, the reference will highlight.
- Note that in **Obsidian** at least, footnotes are rendered until _read-mode_ is accessed.

### **_Syntax_**
```
This is the text that will contain a footnote.[^footnote_1]

We will later reference the footnote by denoting as follows:

[^footnote]: This is the actual reference.
```

## **_Example_**
This is a sentence with footnote. [^footnote]

 [^footnote]: This is the actual footnote.

## 16. References
- [ChristianLempa/cheat-sheets/misc/markdown.md](https://github.com/ChristianLempa/cheat-sheets/blob/main/misc/markdown.md)
- [adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [normal-distribution-density-function](https://en.wikipedia.org/wiki/Normal_distribution)