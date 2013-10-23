---
title       : Introduction to Markdown
subtitle    : 
author      : Jeffrey Leek, Assistant Professor of Biostatistics 
job         : Johns Hopkins Bloomberg School of Public Health
logo        : bloomberg_shield.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
url:
  lib: ../../libraries
  assets: ../../assets
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---
  
## What is Markdown?

### "Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML)."

<br></br>
### \- [**John Gruber, creator of Markdown**](http://daringfireball.net/projects/markdown/) 

---

## Markdown Syntax

### Italics

<br></br>

```markdown
*This text will appear italicized!*
```

<br></br>
*This text will appear italicized!*

---

## Markdown Syntax

### Bold

<br></br>

```markdown
**This text will appear bold!**
```

<br></br>
**This text will appear bold!**  

---

## Markdown Syntax

### Headings

<br></br>

```markdown
## This is a secondary heading
### This is a tertiary heading
```

<br></br>
## This is a secondary heading
### This is a tertiary heading

---

## Markdown Syntax

### Unordered Lists

<br></br>

```markdown
- first item in list
- second item in list
- third item in list
```

<br></br>
- first item in list
- second item in list
- third item in list

---

## Markdown Syntax

### Ordered Lists

<br></br>

```markdown
1. first item in list
2. second item in list
3. third item in list
```

<br></br>

1. first item in list
2. second item in list
3. third item in list

---

## Markdown Syntax

### Code blocks

    ```r
    library(datasets)
    mean(iris$Sepal.Length)
    median(iris$Sepal.Length)
    hist(iris$Sepal.Length)
    ```
    
```r
library(datasets)
mean(iris$Sepal.Length)
median(iris$Sepal.Length)
hist(iris$Sepal.Length)
```

---

## Markdown Syntax

### Inline Code

<br></br>

```markdown
`plot(beaver1$time, beaver1$temp, main="Body Temperature Series of a Beaver")`
```

<br></br>

`plot(beaver1$time, beaver1$temp, main="Body Temperature Series of a Beaver")`

---

## Markdown Syntax

### Links

<br></br>

```markdown
[Johns Hopkin Bloomberg School of Public Health](http://www.jhsph.edu/)
[Download R](http://www.r-project.org/)
[RStudio](http://www.rstudio.com/)
```

<br></br>

[Johns Hopkins Bloomberg School of Public Health](http://www.jhsph.edu/)  
[Download R](http://www.r-project.org/)  
[RStudio](http://www.rstudio.com/)  

---

## Markdown Syntax

### Advanced Linking

<br></br>

```markdown
    I spend so much time reading [R bloggers][1] and [Simply Statisitcs][2]!  
    [1]: http://www.r-bloggers.com/   "R bloggers"  
    [2]: http://simplystatistics.org/ "Simply Statisitcs"  
```

<br></br>

I spend so much time reading [R bloggers][1] and [Simply Statisitcs][2]!

[1]: http://www.r-bloggers.com/   "R bloggers"
[2]: http://simplystatistics.org/ "Simply Statisitcs"

---

## Markdown Syntax

### Newlines

- Newlines require a double space after the end of a line.

```markdown
First line
Second line
```

First line
Second line

```markdown
First line
Second line
```

First line  
Second line

---

## Markdown Resources

- [The Offical Markdown Documentation](http://daringfireball.net/projects/markdown/basics)
- [Github's Markdown Guide](https://help.github.com/articles/github-flavored-markdown)
- [Dillinger - Edit, Export, and Share Markdown Documents](http://www.dillinger.io/)
- [This document on Github](https://github.com/seankross/Introduction-to-Markdown)