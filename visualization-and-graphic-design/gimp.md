# GIMP

[![made-with badge](https://img.shields.io/static/v1?label=Made%20with&message=Obsidian&color=7d5bed&logo=obsidian&labelColor=1a1a1a&style=flat)](https://obsidian.md/)

[![type](https://img.shields.io/static/v1?label=Type&message=documentation&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAi0lEQVRIS+2WMQ7AIAhF/UNXrtP7rz2OYxeqTWxMTBUSxQVXfnzyQQKC8YExL7zAGCNbgIkIsIKVhBw4vbR7unR6Gp0LvwxXd2v+EvkdDpxWXpWlRTyi9/pABRyBJHEHSlxSadxSlV0SsVsqcUml2W/pynWxnsXNisHMRxrCl8qvH3ECnQDuOmy+0zwB4WNxmUKgwwAAAABJRU5ErkJggg==&labelColor=1a1a1a&style=flat)](https://pabloagn.com/documentation/) [![category](https://img.shields.io/static/v1?label=Category&message=visualization-and-graphic-design&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAB9UlEQVRIS6VWMU7DQBDkDAQEdrAoCISCAomCL1DxC95Azy9oeQS/oOIHVFAgREFoCHGCRSzZzEU+63LZ9W6CO/vudmZ2d9Zn1pTPaDSqut2usduHw+FpFEUv7t1fk8LNAkiPDWj3+ADuTPjNvXMxWwGzLCuqqtqwh5MkiY0xEwfOAfrEKFAWUBO4DZQDXgCEqjuouvbZUanUrocpngMMVUkKtKC+WhFQUudAUd8r1PkepJ/w7Tysn4uzkNJlascF9WOASAki6w0xrn19b3Gpps5y3kRfJADPZgr9gJSP0EgDHDiQ/Mp50PfxAmDtuQhsZmb/z0OVhwSkmGrSGp5bGRDp3EFaJ5JaiahdZ2vYNj/JkWVMgW7sgNw2yOW+99gacp7TeFE72OcUrgo4Ho93+/3+D5T9QmGHm0BNSnHgMI7jj9Ai2tElZGCK9S3S+GA4BcNNydBaIuEstu/iLJWCa+pLDm+Nz+xQAsBenucnRVG8asFq0s/Yf9YoVAI21wyn3N4I7M1A8ijWHwB42XrFqIO9YfMRlVqqyXC5ukED3nIEVJcoBXv1lmWa5gIpeeQioyTWVj1uXf0DpgKUZbmfpunXKnVnU9rWDKiTHRSDNkDu36iqIQK/Q+mxU8sBYniL/1EVoJ9Wqwo/5x6Cf9YKv6Em1XbNH5bGfSwvuRe1AAAAAElFTkSuQmCC&labelColor=1a1a1a&style=flat)](https://pabloagn.com/categories/visualization-and-graphic-design/) [![technologies](https://img.shields.io/static/v1?label=Technologies&message=X&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAACXBIWXMAAAsTAAALEwEAmpwYAAAA1klEQVR4nM2RMW7CUBBEnUikIQUIlBJxrrQgJG7ABRBnoUkaWhpoUgWJlgNYbvz/G1dUi1ayoy87rpOtVrszs6OdLPtXlef5UNJXjHHcCwohjMzsKZ3FGN+Bq/e+c0xHGfiWtEznkg6SNnW/dIxjs0YJ2AMnM3tJSFPgHkKY17gBcAQ+zOw5A3aSbsCkdW0NnNOZY2rstpcInJ3cS/SzwGdqtSzLmdusquqtIXWsehVF8QpcJK1qmxt/TMv6wjE/z0leP27i8Ag8inT/axxtAQ+9o/zn9QD3JOiyTjnQEQAAAABJRU5ErkJggg==&labelColor=1a1a1a&style=flat)](https://pabloagn.com/technologies/)

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