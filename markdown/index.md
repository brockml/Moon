---
layout: page
title: Markdown
tags: [markdown, syntax, formatting, atom, html, md, LaTeX]
date: 2018-05-29
comments: false
---

## Introduction
Markdown is a syntax used to format text. It controls the display of a document and allows you to format words, create lists, add images, and more. The syntax uses plain text to make text easy to read, write, and format. Markdown files can be easily converted to HTML for publishing on the web. In fact, it's how this web page was created!

---

## Getting Setup
There are a variety of markdown editors to choose from. The one that we will be using for this tutorial is Atom. It's cross platform, open source, and has over 7000 packages that can be installed to enhance the editor.

[![](/assets/img/Atom_logo.png)](https://atom.io/)

Click the image above to go to Atom's website to download the software.
After downloading, install the packages: markdown-preview-plus and toolbar-markdown-writer by clicking on Packages > Settings View > InstallPackages/Themes

![](/assets/img/install_packages.png)

Type the name of the package into the search bar and click Install.
Open a new markdown file by pressing Command-N.
To preview the markdown document press Control-Shift-M.

Your screen should now look like this:

![](/assets/img/preview.png)

Begin typing in the 'untitled' tab and the formatted text will appear in the 'untitled Preview' tab. 

---

## Basic Syntax

--- 

### Headers
The number of signs you use corresponds to the heading level.

```
# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
#### Heading Level 5
```

The rendered output:
# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
#### Heading Level 5

---

### Paragraphs
Separate lines of text with a blank line.

```
Markdown is a syntax used to format text.

Use Markdown language to format web pages.
```

The rendered output:

Markdown is a syntax used to format text.

Use Markdown language to format web pages.

---

### Blockquotes
Add a ```>``` in front of a paragraph.

```
> Markdown is a syntax used to format text. It controls the display of a document and allows you to format words, create lists, add images, and more. The syntax uses plain text to make text easy to read, write, and format. Markdown files can be easily converted to HTML for publishing on the web. In fact, it's how this web page was created!
```

The rendered output:
> Markdown is a syntax used to format text. It controls the display of a document and allows you to format words, create lists, add images, and more. The syntax uses plain text to make text easy to read, write, and format. Markdown files can be easily converted to HTML for publishing on the web. In fact, it's how this web page was created!

---

### Line Breaks
End a line with two or more spaces and then press return.

```
Markdown is a syntax used to format text.
Use Markdown language to format web pages.
```

The rendered output:

Markdown is a syntax used to format text.
Use Markdown language to format web pages.

---

### Emphasis
Add emphasis to words using italics, bold, or both.

```
*italics* 
_italics_ 
**bold** 
__bold__ 
***both*** 
___both___ 
__*both*__ 
**_both_**
```

The rendered output:

*italics*  
_italics_  
**bold**  
__bold__  
***both***  
___both___  
__*both*__  
**_both_**  

---

### Strikethroughs
Use two tildes before and after to strikethrough words

```
~~Life does not exist on other planets.~~
```

Rendered output:

~~Life does not exist on other planets.~~

---

### Lists
#### Ordered Lists
Use numbers followed by periods.

```
1. First things First
2. Second things Second
3. Third things Third
```

The rendered output:
1. First things First
2. Second things Second
3. Third things Third

Indent items to create a nested list.

```
1. First things First
  1. This thing too
  2. Also this
2. Second things Second
3. Third things Third
```

The rendered output:
1. First things First
    1. This thing too
    2. Also this
2. Second things Second
3. Third things Third

#### Unordered Lists
Use asterisks, dashes, or plus signs.

```
* First things First
* Second things Second
* Third things Third

- First things First
- Second things Second
- Third things Third

+ First things First
+ Second things Second
+ Third things Third
```

The rendered output:
* First things First
* Second things Second
* Third things Third

- First things First
- Second things Second
- Third things Third

+ First things First
+ Second things Second
+ Third things Third

Indent items to create a nested list.

```
* First things First
  - This thing tool
  - Also this
* Second things Second
* Third things Third
```

The rendered output:
* First things First
  - This thing tool
  - Also this
* Second things Second
* Third things Third

#### Task Lists
Use dashes and brackets in front of task list items. Place an x in between the brackets to check off an item.

```
- [ ] Label tubes
- [x] Setup notebook
- [ ] Process samples
```

The rendered output:
- [ ] Label tubes
- [x] Setup notebook
- [ ] Process samples

---

### Code
Use tick marks to denote something as code.

```
`pwd`
```

The rendered output:

`pwd`

---

### Code Blocks
Use three tick marks (```) or three tildes (~~~) before and after code to create code blocks.

The rendered output:
```
```

---

### Horizontal Lines
Use three or more dashes, underscores, or asterisks on a line by themselves.

```
---

___

***
```

The rendered output:

---

---

### Tables
Create a table using pipes and dashes (at least 3 dashes must be used).

```
| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
|   data   |   data   |   data   |
```
The rendered output:

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
|   data   |   data   |   data   |

The first and last pipe characters are optional. Whitespace is ignored. Also, columns do not need to be aligned or have the same number of characters.

```
 Column 1|Column 2|Column 3
 ----| ------| --------
   data |   data |   data
```

The rendered output:

Column 1|Column 2|Column 3
----| ------| --------
  data |   data |   data

#### Table Alignment
Use colons to specify alignment.

```
| Column 1 | Column 2 | Column 3 | Column 4 |
| -------- | :------- | -------: | :------: |
| default  |   left   |   right  | centered |
```

The rendered output:

| Column 1 | Column 2 | Column 3 | Column 4 |
| -------- | :------- | -------: | :------: |
| default  |   left   |   right  | centered |

---

### Links
Place the link text in brackets followed by the URL in parentheses.

```
For more Markdown syntax go to [this site](https://www.markdownguide.org/).
```

The rendered output:

For more Markdown syntax go to [this site](https://www.markdownguide.org/).

---

### Images
To insert an image:

```
![](/assets/img/ship_deck.png)
```

The rendered output:

![](/assets/img/ship_deck.png)

---

### Images with Links
To add a link to an image:

```
[![](/assets/img/ship_deck.png)](https://github.com/brockml/brockml.github.io/blob/master/assets/img/ship_deck.png)
```

The rendered output:

[![](/assets/img/ship_deck.png)](https://github.com/brockml/brockml.github.io/blob/master/assets/img/ship_deck.png)

---

### Escaping Characters
Use a backslash in front of a character to display a literal character that would've been used to format text in Markdown.

```
\- This dash does not signify an unordered list.
```

The rendered output:

\- This dash does not signify an unordered list.

---

## Formatting Mathematical Expressions and Equations
Markdown uses standard LaTeX syntax for mathematical expressions. LaTeX is a type-setting system that is the standard for publication of scientific documents. I'm going to go through how to write common expressions and format equations, but for more complex things please consult [this LaTeX guide](https://www.sharelatex.com/learn/Mathematical_expressions).

### Inline and Displayed Expressions
Mathematical Expressions and equations can be expressed either inline with text using `$` or be displayed on their own line by using `$$`

```
Inline: Atmospheric $CO_2$ concentration is currently 410 ppm.
Displayed: To calculate the kinetic energy of an object use the formula: $$KE = \frac{1}{2}mv^2$$
```

The rendered output:

Inline: Atmospheric $$CO_2$$ concentration is currently 410 ppm.  
Displayed: To calculate the kinetic energy of an object use the formula:  

$$KE = \frac{1}{2}mv^2$$

---

### Common Math Symbols

#### Greek letters:

| Syntax | Rendered Output|
| :----: | :---: |
| `$\alpha$` | $$alpha$$ |
| `$\beta$` | $$\beta$$ |
| `$\gamma$` | $$\gamma$$ |
| `$\rho$` | $$\rho$$ |

#### Binary operators:

| Syntax | Rendered Output|
| :----: | :---: |
| `$\times$`   | $$\times$$  |
| `$\div$`   | $$\div$$  |
| `$\pm$`  |  $$\pm$$ |
| `$\mp$`   | $$\mp$$  |

#### Relation operators:

| Syntax | Rendered Output|
| :----: | :---: |
| `$\leq$`   | $$\leq$$  |
| `$\geq$`   |  $$\geq$$ |
| `$\equiv$`   | $$\equiv$$  |
| `$\sim$`   |  $$\sim$$ |
| `$\simeq$`   | $$\simeq$$  |
| `$\approx$`   |  $$\approx$$ |
| `$\propto$`   |  $$\propto$$ |

#### Arrow Symbols:

| Syntax | Rendered Output|
| :----: | :---: |
| `$\leftarrow$`   | $$\leftarrow$$  |
| `$\rightarrow$`  |  $$\rightarrow$$ |
| `$\leftrightarrow$`   |  $$\leftrightarrow$$ |
| `$\leftharpoonup$`   | $$\leftharpoonup$$  |
| `$\leftharpoondown$`   | $$\leftharpoondown$$  |
| `$\rightharpoonup$`   |  $$\rightharpoonup$$ |
| `$\rightharpoondown$`   |  $$\rightharpoondown$$ |

#### Other Symbols:

| Syntax | Rendered Output|
| :----: | :---: |
| `$\infty$`  | $$\infty$$  |
| `$\pi$`   | $$\pi$$  |
| `$\sum$`   | $$\sum$$  |
| `$\prod$`   | $$\prod$$  |
| `$\coprod$`   | $$\coprod$$  |
| `$\int$`   | $$\int$$  |
| `$\oint$`   | $$\oint$$  |
| `$\cos$`   | $$\cos$$  |
| `$\ln$`   | $$\ln$$  |

#### Accents:

| Syntax | Rendered Output|
| :----: | :---: |
| `$\hat{a}$`   | $$\hat{a}$$  |
| `$\check{a}$`  | $$\check{a}$$  |
| `$\acute{a}$`   | $$\acute{a}$$  |
| `$\grave{a}$`   | $$\grave{a}$$  |
| `$\bar{a}$`   |  $$\bar{a}$$ |
| `$\vec{a}$`   |  $$\vec{a}$$ |
| `$\dot{a}$`   |  $$\dot{a}$$ |
| `$\ddot{a}$`   | $$\ddot{a}$$  |
| `$\breve{a}$`   | $$\breve{a}$$  |
| `$\tilde{a}$`   |  $$\tilde{a}$$ |

---

### Subscripts and Superscripts
Use an underscore to denote a subscript and a caret to denote a superscript

#### Basic subscripts and superscripts:
```
Subscript: $H_2O_2$
Superscript: $a^2 + b^2 = c^2$
Combined: $_1^2H$ or $a_3^2$
```

The rendered output:

Subscript: $$H_2O_2$$  
Superscript: $$a^2 + b^2 = c^2$$  
Combined: $$_1^2H$$ or $$a_3^2$$

#### Long subscripts and superscripts:

```
Subscript: $y_{ij}$
Superscript: $a^{245}$
Combined: $_{80}^{200}Hg$
```

The rendered output:

Subscript: $$y_{ij}$$  
Superscript: $$a^{245}$$  
Combined: $$_{80}^{200}Hg$$

#### Nested subscripts and superscripts:

```
$(a-b^2)^2$
```

The rendered output:

$$(a-b^2)^2$$

#### Operators using subscripts and superscripts:

**Sums:**

```
$\sum_{i=1}^{\infty}$
```

The rendered output:

$$\sum_{i=1}^{\infty}$$

**Products:**

```
$\prod_p$
```

The rendered output:

$$\prod_p$$

**Integrals:**

```
$\int_{i=0}^n$
```

The rendered output:

$$\int_{i=0}^n$$

**Limits:**

```
$\lim_{x\to\infty} f(x)$
```

The rendered output:

$$\lim_{x\to\infty} f(x)$$

---

### Fractions

#### Basic Fractions:
The first pair of braces is the numerator, the second is the denominator.

```
$\frac{1}{4}$
$\frac{1}{1-x}^2$
$\frac{1}{(1-x)^2}$
```

The rendered output:

$$\frac{1}{4}$$  

$$\frac{1}{1-x}^2$$  

$$\frac{1}{(1-x)^2}$$

#### Nested Fractions:

```
$\frac{1+\frac{a}{y}}{z}$
$\frac{1+\frac{a}{y}}{\frac{z}{2}}$
```

The rendered output:

$$\frac{1+\frac{a}{y}}{z}$$  

$$\frac{1+\frac{a}{y}}{\frac{z}{2}}$$

---

### Binomials

```
$\binom{n}{k} = \frac{n!}{k!(n-k)!}$
```

The rendered output:

$$\binom{n}{k} = \frac{n!}{k!(n-k)!}$$
