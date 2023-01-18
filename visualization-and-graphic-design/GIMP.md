# GIMP
**GIMP** is a . 

Main extension used is `.xfc`.

## 0. Table of Contents
1. [Section 1](#1-headers)
2. [Section 2](#2-horizontal-rule)
3. [Section 3](#3-emphasis)
4. [Section 4](#4-line-breaks)
5. [Section 5](#5-lists)
	1. [Subsection 5.1](#i-ordered-lists)
	2. [Subsection 5.2](#ii-unordered-lists)
6. [Section 6](#5-lists)
7. [Footnotes](#15-footnotes)
8. [References](#16-references)

## 1. Python Scripts
- _Headers_ serve as hierarchy differentiators, just as in any typical word processor. 

### 1.1 Bulk Export

#### **_Syntax_**
```Python
import glob
for fname in glob.glob("*.xcf"):
    img = pdb.gimp_file_load(fname, fname)
    img.flatten()
    new_image = pdb.gimp_image_duplicate(img)
    layer = pdb.gimp_image_merge_visible_layers(new_image, CLIP_TO_IMAGE)
    new_name = fname[:-4] + "_REDUCED.jpg"
    pdb.gimp_file_save(new_image, layer, new_name, new_name)
```

#### **_Example_**



## 14. Footnotes
- _Footnotes_ can be added by enclosing any keyword in squared brackets and ading the caret symbol before keyword `[^footnote_1]`.
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

## 15. References
- [ChristianLempa/cheat-sheets/misc/markdown.md](https://github.com/ChristianLempa/cheat-sheets/blob/main/misc/markdown.md)
- [adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [normal-distribution-density-function](https://en.wikipedia.org/wiki/Normal_distribution)