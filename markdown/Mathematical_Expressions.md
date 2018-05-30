---
layout: page
title: Markdown
tags: [markdown, syntax, formatting, atom, html, md, LaTeX]
date: 2018-05-29
comments: false
---

## Introduction
If you haven't downloaded Atom and installed the packages, please consult the guide on 'Basic Syntax' to get setup! Markdown uses standard LaTeX syntax for mathematical expressions. LaTeX is a type-setting system that is the standard for publication of scientific documents. I'm going to go through how to write common expressions and format equations, but for more complex things please consult [this LaTeX guide](https://www.sharelatex.com/learn/Mathematical_expressions).

---

### Inline and Displayed Expressions
Mathematical Expressions and equations can be expressed either inline with text using `$` or be displayed on their own line by using `$$`

```
Inline: Atmospheric $CO_2$ concentration is currently 410 ppm.
Displayed: To calculate the kinetic energy of an object use the formula: $$KE = \frac{1}{2}mv^2$$
```

The rendered output:

Inline: Atmospheric $$CO_2$$ concentration is currently 410 ppm.
Displayed: To calculate the kinetic energy of an object use the formula: $$KE = \frac{1}{2}mv^2$$

---

### Common Math Symbols

#### Greek letters

| Syntax | Rendered Output|
| :----: | :---: |
| `$\alpha$` | $$alpha$$ |
| `$\beta$` | $$\beta$$ |
| `$\gamma$` | $$\gamma$$ |
| `$\rho$` | $$\rho$$ |

#### Binary operators

| Syntax | Rendered Output|
| :----: | :---: |
| `$\times$`   | $$\times$$  |
| `$\div$`   | $$\div$$  |
| `$\pm$`  |  $$\pm$$ |
| `$\mp$`   | $$\mp$$  |

#### Relation operators

| Syntax | Rendered Output|
| :----: | :---: |
| `$\leq$`   | $$\leq$$  |
| `$\geq$`   |  $$\geq$$ |
| `$\equiv$`   | $$\equiv$$  |
| `$\sim$`   |  $$\sim$$ |
| `$\simeq$`   | $$\simeq$$  |
| `$\approx$`   |  $$\approx$$ |
| `$\propto$`   |  $$\propto$$ |

#### Arrow Symbols

| Syntax | Rendered Output|
| :----: | :---: |
| `$\leftarrow$`   | $$\leftarrow$$  |
| `$\rightarrow$`  |  $$\rightarrow$$ |
| `$\leftrightarrow$`   |  $$\leftrightarrow$$ |
| `$\leftharpoonup$`   | $$\leftharpoonup$$  |
| `$\leftharpoondown$`   | $$\leftharpoondown$$  |
| `$\rightharpoonup$`   |  $$\rightharpoonup$$ |
| `$\rightharpoondown$`   |  $$\rightharpoondown$$ |

#### Other Symbols

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

#### Accents

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

#### Operators using subscripts and supscripts:

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
