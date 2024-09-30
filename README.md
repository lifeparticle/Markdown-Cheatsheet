<h1 align="center">
  :black_circle: The Ultimate Markdown Cheat Sheet :black_circle:
</h1>

<div align="center">

  <a href="https://github.com/lifeparticle/Markdown-Cheatsheet/actions/workflows/readme-checker.yml">
    <img src="https://github.com/lifeparticle/Markdown-Cheatsheet/actions/workflows/readme-checker.yml/badge.svg" alt=".github/workflows/readme-checker.yml">
  </a>

</div>

<a name="top"></a>

<br/>

> [!IMPORTANT]
> Check out the official documentation on [GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) to learn more about writing and formatting syntax. Additionally, you can read the latest updates and features on Markdown by visiting the [GitHub changelog posts](https://github.blog/changelog/label/markdown/).

- [Introduction](#introduction)
- [Headings](#headings)
- [Text styles](#text-styles)
  - [Normal](#normal)
  - [Bold](#bold)
  - [Italic](#italic)
  - [Bold and Italic](#bold-and-italic)
  - [Blockquotes](#blockquotes)
  - [Monospaced](#monospaced)
  - [Underlined](#underlined)
  - [Strike-through](#strike-through)
  - [Boxed](#boxed)
  - [Subscript](#subscript)
  - [Superscript](#superscript)
  - [Text Color](#text-color)
  - [Multiline](#multiline)
- [Syntax Highlighting](#syntax-highlighting)
  - [Inline code](#inline-code)
  - [Code block](#code-block)
  - [Diff Code block](#diff-code-block)
- [Alignments](#alignments)
- [Tables](#tables)
- [Links](#links)
  - [Inline](#inline)
  - [Reference](#reference)
  - [Footnote](#footnote)
  - [Relative](#relative)
  - [Auto](#auto)
  - [Section](#section)
  - [Hover](#hover)
  - [Enclosed](#enclosed)
  - [Highlight words and link it to a URL](#highlight-words-and-link-it-to-a-url)
- [Images](#images)
  - [Theme](#theme)
    - [Using picture tag](#using-picture-tag)
    - [Using dark and light mode](#using-dark-and-light-mode)
- [Badges](#badges)
- [Lists](#lists)
  - [Ordered](#ordered)
  - [Unordered](#unordered)
  - [Task](#task)
- [Buttons](#buttons)
  - [Button with emoji](#button-with-emoji)
- [Collapsible items (28 July 2023)](#collapsible-items-28-july-2023)
- [Horizontal Rule](#horizontal-rule)
- [Diagrams (19 July 2022)](#diagrams-19-july-2022)
- [Mathematical expressions (19 July 2022)](#mathematical-expressions-19-july-2022)
- [Alerts (8 January 2024)](#alerts-8-january-2024)
- [Mention people and teams](#mention-people-and-teams)
- [Reference issues and pull requests](#reference-issues-and-pull-requests)
- [Color models](#color-models)
- [View Code](#view-code)
- [Code in titles](#code-in-titles)
- [Reference Labels](#reference-labels)
- [Miscellaneous](#miscellaneous)
  - [Comments](#comments)
  - [Escaping Markdown Characters](#escaping-markdown-characters)
  - [Emojis](#emojis)
  - [Line break](#line-break)
  - [Back to top](#back-to-top)
- [Bitbucket](#bitbucket)
- [Azure DevOps Project wiki](#azure-devops-project-wiki)
- [MDX](#mdx)
- [Tools](#tools)

# Introduction

Markdown is a way of writing rich-text (formatted text) content using plain text formatting syntax. It is also a tool that converts the plain text formatting to HTML.

- **2004:** [John Gruber](https://daringfireball.net/projects/markdown/) developed Markdown.
- **2014:** [CommonMark](https://commonmark.org/) was established as a standard specification for Markdown to resolve inconsistencies and ambiguities in Markdown implementations. This initiative was spearheaded by [John MacFarlane](https://github.com/jgm) and backed by other Markdown enthusiasts to ensure a reliable and consistent specification.

This guide will provide you with a comprehensive understanding of the key commands in [GitHub Flavored Markdown (GFM)](https://github.github.com/gfm/), it is a strict superset of CommonMark. You can read the full article, [The Ultimate Markdown Cheat Sheet
](https://towardsdatascience.com/the-ultimate-markdown-cheat-sheet-3d3976b31a0) on Medium.

# Headings

```md
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
<!-- omit in toc -->
# Heading 1
<!-- omit in toc -->
## Heading 2
<!-- omit in toc -->
### Heading 3
<!-- omit in toc -->
#### Heading 4
<!-- omit in toc -->
##### Heading 5
<!-- omit in toc -->
###### Heading 6

```md
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

<!-- omit in toc -->
<h1>Heading 1</h1>
<!-- omit in toc -->
<h2>Heading 2</h2>
<!-- omit in toc -->
<h3>Heading 3</h3>
<!-- omit in toc -->
<h4>Heading 4</h4>
<!-- omit in toc -->
<h5>Heading 5</h5>
<!-- omit in toc -->
<h6>Heading 6</h6>

```md
Heading 1
=
Heading 2
-
```

<!-- omit in toc -->
Heading 1 <!-- markdownlint-disable MD003 -->
=
<!-- omit in toc -->
Heading 2 <!-- markdownlint-disable MD003 -->
-

# Text styles

## Normal

```md
The quick brown fox jumps over the lazy dog.
```

The quick brown fox jumps over the lazy dog.

## Bold

Mac: <kbd>command+B</kbd>

Windows: <kbd>control+B</kbd>

```md
**The quick brown fox jumps over the lazy dog.**
__The quick brown fox jumps over the lazy dog.__
<strong>The quick brown fox jumps over the lazy dog.</strong>
```

**The quick brown fox jumps over the lazy dog.**

<!-- markdownlint-disable-next-line MD050 -->
__The quick brown fox jumps over the lazy dog.__

<strong>The quick brown fox jumps over the lazy dog.</strong>

## Italic

Mac: <kbd>command+I</kbd>

Windows: <kbd>control+I</kbd>

```md
*The quick brown fox jumps over the lazy dog.*
_The quick brown fox jumps over the lazy dog._
<em>The quick brown fox jumps over the lazy dog.</em>
```

*The quick brown fox jumps over the lazy dog.*

<!-- markdownlint-disable-next-line MD049 -->
_The quick brown fox jumps over the lazy dog._

<em>The quick brown fox jumps over the lazy dog.</em>

## Bold and Italic

```md
**_The quick brown fox jumps over the lazy dog._**
<strong><em>The quick brown fox jumps over the lazy dog.</em></strong>
```
<!-- markdownlint-disable-next-line MD049 -->
**_The quick brown fox jumps over the lazy dog._**

<strong><em>The quick brown fox jumps over the lazy dog.</em></strong>

## Blockquotes

Mac: <kbd>command+shift+.</kbd>

Windows: <kbd>control+shift+.</kbd>

```md
> The quick brown fox jumps over the lazy dog.

<br>

> The quick brown fox jumps over the lazy dog.
>
> The quick brown fox jumps over the lazy dog.
>
> The quick brown fox jumps over the lazy dog.

<br>

> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.

<br>

> **The quick brown fox** *jumps over the lazy dog.*
```

> The quick brown fox jumps over the lazy dog.

<br>

> The quick brown fox jumps over the lazy dog.
>
> The quick brown fox jumps over the lazy dog.
>
> The quick brown fox jumps over the lazy dog.

<br>

> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.

<br>

> **The quick brown fox** *jumps over the lazy dog.*

## Monospaced

```md
<samp>The quick brown fox jumps over the lazy dog.</samp>
```

<samp>The quick brown fox jumps over the lazy dog.</samp>

## Underlined

```md
<ins>The quick brown fox jumps over the lazy dog.</ins>
```

<ins>The quick brown fox jumps over the lazy dog.</ins>

## Strike-through

```md
~~The quick brown fox jumps over the lazy dog.~~
```

~~The quick brown fox jumps over the lazy dog.~~

```md
<pre>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strike>Sed do eiusmod tempor incididunt ut labore et dolore magna
aliqua.</strike> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <strike>Excepteur sint
occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</strike>
</pre>
```

<pre>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strike>Sed do eiusmod tempor incididunt ut labore et dolore magna
aliqua.</strike> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <strike>Excepteur sint
occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</strike>
</pre>

````md
<strike>

```js
console.log('Error');
```

</strike>
````

<strike>

```js
console.log('Error');
```

</strike>

## Boxed

```md
<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>
```

<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>

## Subscript

```md
log<sub>2</sub>(x)
Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
```

log<sub>2</sub>(x)

Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>

## Superscript

```md
2 <sup>53-1</sup> and -2 <sup>53-1</sup>
Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>
```

2 <sup>53-1</sup> and -2 <sup>53-1</sup>

Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>

## Text Color

Using [MathJax](#mathematical-expressions-19-july-2022) syntax:

| Color Name      | Code                                                                                         | Example                                                        |
|-----------------|----------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| Apricot         | `$\color{Apricot}{The\ quick\ brown\ fox\ jumps\ over\ the\ lazy\ dog.}$`                    | $\color{Apricot}{The\ quick\ brown\ fox\ jumps\ over\ the\ lazy\ dog.}$      |
| Aquamarine      | `$\color{Aquamarine}{The\ quick\ brown\ fox\ jumps\ over\ the\ lazy\ dog.}$`                 | $\color{Aquamarine}{The\ quick\ brown\ fox\ jumps\ over\ the\ lazy\ dog.}$   |
| Bittersweet     | `$\color{Bittersweet}{The\ quick\ brown\ fox\ jumps\ over\ the\ lazy\ dog.}$`                | $\color{Bittersweet}{The\ quick\ brown\ fox\ jumps\ over\ the\ lazy\ dog.}$  |
| Black           | `$\color{Black}{The\ quick\ brown\ fox\ jumps\ over\ the\ lazy\ dog.}$`                      | $\color{Black}{The\ quick\ brown\ fox\ jumps\ over\ the\ lazy\ dog.}$        |

[Full Table](./MathJax.md)

## Multiline

The quick\
brown fox\
jumps over\
the lazy dog.

```md
The quick\
brown fox\
jumps over\
the lazy dog.
```

# Syntax Highlighting

## Inline code

A class method is an instance method of the class object. When a new class is created, an object of type `Class` is initialized and assigned to a global constant (Mobile in this case).

You can use <kbd>command + e </kbd> on Mac or <kbd>control + e</kbd> on Windows to insert inline code.

## Code block

<!-- markdownlint-disable MD040 -->

```
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```

<!-- markdownlint-enable MD040 -->

````md
```
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```
````

```java
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```

````md
```java
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```
````

Refer to [this](https://github.com/github-linguist/linguist/blob/master/lib/linguist/languages.yml) and [this](https://github.com/github-linguist/linguist/tree/master/vendor) GitHub document to find all the valid keywords.

## Diff Code block

```diff
## git diff a/test.txt b/test.txt
diff --git a/a/test.txt b/b/test.txt
index 309ee57..c995021 100644
--- a/a/test.txt
+++ b/b/test.txt
@@ -1,8 +1,6 @@
-The quick brown fox jumps over the lazy dog
+The quick brown fox jumps over the lazy cat

 a
-b
 c
 d
-e
 f
```

````md
```diff
## git diff a/test.txt b/test.txt
diff --git a/a/test.txt b/b/test.txt
index 309ee57..c995021 100644
--- a/a/test.txt
+++ b/b/test.txt
@@ -1,8 +1,6 @@
-The quick brown fox jumps over the lazy dog
+The quick brown fox jumps over the lazy cat

 a
-b
 c
 d
-e
 f
```
````

```diff
- Text in Red
+ Text in Green
! Text in Orange
# Text in Gray
@@ Text in Purple and bold @@
```

````md
```diff
- Text in Red
+ Text in Green
! Text in Orange
# Text in Gray
@@ Text in Purple and bold @@
```
````

# Alignments

```md
<p align="left">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
```

<p align="left">
<!-- markdownlint-disable-next-line MD013 -->
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10" alt="Vintage-style alarm clock with Roman numerals on its face, set on a surface covered with newspaper, with a blurred background."/>
</p>

```md
<p align="center">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
```

<p align="center">
<!-- markdownlint-disable-next-line MD013 -->
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10" alt="Vintage-style alarm clock with Roman numerals on its face, set on a surface covered with newspaper, with a blurred background."/>
</p>

```md
<p align="right">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>
```

<p align="right">
<!-- markdownlint-disable-next-line MD013 -->
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10" alt="Vintage-style alarm clock with Roman numerals on its face, set on a surface covered with newspaper, with a blurred background."/>
</p>

```md
<h3 align="center"> My latest Medium posts </h3>
```

<!-- omit in toc -->
<h3 align="center"> My latest Medium posts </h3>

# Tables

```md
<table>
<tr>
<td width="33%"">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
</tr>
</table>
```

<table>
<tr>
<td width="33%"">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
</tr>
</table>

```md
| Default | Left align | Center align | Right align |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |

| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |

Default    | Left align | Center align | Right align
---------- | :--------- | :----------: | ----------:
9999999999 | 9999999999 | 9999999999   | 9999999999
999999999  | 999999999  | 999999999    | 999999999
99999999   | 99999999   | 99999999     | 99999999
9999999    | 9999999    | 9999999      | 9999999
```

| Default | Left align | Center align | Right align |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |

| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |

<!-- markdownlint-disable MD055 -->
Default    | Left align | Center align | Right align
---------- | :--------- | :----------: | ----------:
9999999999 | 9999999999 | 9999999999   | 9999999999
999999999  | 999999999  | 999999999    | 999999999
99999999   | 99999999   | 99999999     | 99999999
9999999    | 9999999    | 9999999      | 9999999
<!-- markdownlint-enable MD055 -->

```md
<table>
<tr>
<th>Heading 1</th>
<th>Heading 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>
```

<table>
<tr>
<th>Heading 1</th>
<th>Heading 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>

```md
| A | B | C |
|---|---|---|
| 1 | 2 | 3 <br/> 4 <br/> 5 |
```

| A | B | C |
|---|---|---|
| 1 | 2 | 3 <br/> 4 <br/> 5 |

```md
<table>
<tr>
<th>Before Hoisting</th>
<th>After Hoisting</th>
</tr>
<tr>
<td>
<pre lang="js">
console.log(fullName); // undefined
fullName = "Dariana Trahan";
console.log(fullName); // Dariana Trahan
var fullName;
</pre>
</td>
<td>
<pre lang="js">
var fullName;
console.log(fullName); // undefined
fullName = "Dariana Trahan";
console.log(fullName); // Dariana Trahan
</pre>
</td>
</tr>
</table>
```

<table>
<tr>
<th>Before Hoisting</th>
<th>After Hoisting</th>
</tr>
<tr>
<td>
<pre lang="js">
console.log(fullName); // undefined
fullName = "Dariana Trahan";
console.log(fullName); // Dariana Trahan
var fullName;
</pre>
</td>
<td>
<pre lang="js">
var fullName;
console.log(fullName); // undefined
fullName = "Dariana Trahan";
console.log(fullName); // Dariana Trahan
</pre>
</td>
</tr>
</table>

# Links

## Inline

```md
[The-Ultimate-Markdown-Cheat-Sheet](https://github.com/lifeparticle/Markdown-Cheatsheet)
```

[The-Ultimate-Markdown-Cheat-Sheet](https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet)

## Reference

```md
[The-Ultimate-Markdown-Cheat-Sheet][reference text]

[The-Ultimate-Markdown-Cheat-Sheet][1]

[Markdown-Cheat-Sheet]

[reference text]: https://github.com/lifeparticle/Markdown-Cheatsheet
[1]: https://github.com/lifeparticle/Markdown-Cheatsheet
[Markdown-Cheat-Sheet]: https://github.com/lifeparticle/Markdown-Cheatsheet
```

[The-Ultimate-Markdown-Cheat-Sheet][reference text]

[The-Ultimate-Markdown-Cheat-Sheet][1]

[Markdown-Cheat-Sheet]

[reference text]: https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet
[1]: https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet
[Markdown-Cheat-Sheet]: https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet

## Footnote

Footnote.[^1]

Some other important footnote.[^2]

[^1]: This is footnote number one.
[^2]: Here is the second footnote.

```md
Footnote.[^1]

Some other important footnote.[^2]

[^1]: This is footnote number one.
[^2]: Here is the second footnote.
```

<img width="264" alt="Screen Shot 2024-02-06 at 8 23 52 pm" src="https://github.com/lifeparticle/Markdown-Cheatsheet/assets/1612112/f55f13ff-8566-48f8-9353-edf3474523fd">

## Relative

```md
[Example of a relative link](rl.md)
```

[Example of a relative link](rl.md)

## Auto

```md
Visit https://github.com/
```

Visit https://github.com/

```md
Email at example@example.com
```

Email at example@example.com

## Section

<img width="503" alt="Screen Shot 2024-02-04 at 12 49 07 pm" src="https://github.com/lifeparticle/Markdown-Cheatsheet/assets/1612112/fd69c9d9-82d7-44ce-a1ed-2e8d48881097">

## Hover

You can use [BinaryTree](https://binarytree.dev/ "Array of Developer Productivity Tools Designed to Help You Save Time") to create markdown tables.

<!-- markdownlint-disable MD051 -->
You can use [BinaryTree](## "Array of Developer Productivity Tools Designed to Help You Save Time") to create markdown tables.

## Enclosed

```md
<https://github.com/>
```

<https://github.com/>

## Highlight words and link it to a URL

```md
[BinaryTree](https://binarytree.dev/)
```

[BinaryTree](https://binarytree.dev/)

![Jun-15-2024 09-55-51](https://github.com/lifeparticle/Markdown-Cheatsheet/assets/1612112/68d9c7a9-6b05-472f-bbc6-c1e180674502)

# Images

Alt text and title are optional.

```md
![alt text](https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80 "Title text")
```

![alt text](https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80)

```md
![alt text][image]

[image]: https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80 "Title text"
```

![alt text][image]

[image]: https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80 "Title text"

```md
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
```

<!-- markdownlint-disable-next-line MD013 -->
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10" alt="alt text"/>

<img src="https://media.giphy.com/media/qLHzYjlA2FW8g/giphy.gif" alt="GIF of students in a grand hall joyfully throwing their graduation caps into the air in celebration, with large banners and lit torches decorating the background."/>

```md
<img src="https://media.giphy.com/media/qLHzYjlA2FW8g/giphy.gif" />
```

<img src="https://img.shields.io/badge/theultimatemarkdowncheatsheet-brightgreen.svg" alt="Green button with the text 'theultimatemarkdowncheatsheet' in white letters."/>

```md
<img src="https://img.shields.io/badge/theultimatemarkdowncheatsheet-brightgreen.svg" />
```

[![BinaryTree](https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_light.png)](https://binarytree.dev/)

```md
[![BinaryTree](https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_light.png)](https://binarytree.dev/)
```

<!-- markdownlint-disable-next-line MD013 -->
<a href='https://binarytree.dev/' target='_blank'> <img src='https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_light.png' alt="Logo of BinaryTree featuring a hexagonal icon and the text 'BINARY TREE' in capital letters to the right of the icon."/> </a>

```md
<a href='https://binarytree.dev/' target='_blank'> <img src='https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_light.png' /> </a>
```

## Theme

### Using picture tag

The HTML `<picture>` element, along with the `prefers-color-scheme` media feature, enables you to dynamically adjust images according to the user's color scheme preference, providing options for both light and dark modes.

For example, the code snippet below demonstrates how to display a dark-themed BinaryTree logo when the user's device is set to a dark mode, and a light-themed BinaryTree logo for light mode settings:

```md
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_light.png">
  <img alt="BinaryTree" src="https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_light.png" width="200">
</picture>
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_light.png">
  <img alt="BinaryTree" src="https://github.com/lifeparticle/lifeparticle/blob/master/gh_social_light.png" width="200">
</picture>

### Using dark and light mode

```md
[![Badge][Logo-dark]](https://binarytree.dev#gh-dark-mode-only)
[![Badge][Logo-light]](https://binarytree.dev#gh-light-mode-only)

[Logo-dark]: https://github-readme-stats.vercel.app/api?username=lifeparticle&theme=graywhite&show_icons=true#gh-light-mode-only
[Logo-light]: https://github-readme-stats.vercel.app/api?username=lifeparticle&theme=dark&show_icons=true#gh-dark-mode-only
```

[![Badge][Logo-dark]](https://binarytree.dev#gh-dark-mode-only)
[![Badge][Logo-light]](https://binarytree.dev#gh-light-mode-only)

[Logo-light]: https://github-readme-stats.vercel.app/api?username=lifeparticle&theme=graywhite&show_icons=true#gh-light-mode-only
[Logo-dark]: https://github-readme-stats.vercel.app/api?username=lifeparticle&theme=dark&show_icons=true#gh-dark-mode-only

```md
<a href="https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only">
  <img src="https://github-readme-stats.vercel.app/api?username=lifeparticle&theme=graywhite&show_icons=true#gh-light-mode-only" width="350"  alt="This image shows a summary of Mahbub Zaman's GitHub statistics."/>
</a>
<a href="https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only">
  <img src="https://github-readme-stats.vercel.app/api?username=lifeparticle&theme=dark&show_icons=true#gh-dark-mode-only" width="350"  alt="This image shows a summary of Mahbub Zaman's GitHub statistics."/>
</a>
```

<a href="https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only">
  <img src="https://github-readme-stats.vercel.app/api?username=lifeparticle&theme=graywhite&show_icons=true#gh-light-mode-only" width="350"  alt="This image shows a summary of Mahbub Zaman's GitHub statistics."/>
</a>
<a href="https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only">
  <img src="https://github-readme-stats.vercel.app/api?username=lifeparticle&theme=dark&show_icons=true#gh-dark-mode-only" width="350"  alt="This image shows a summary of Mahbub Zaman's GitHub statistics."/>
</a>

# Badges

```md
![GitHub forks](https://img.shields.io/github/forks/lifeparticle/Markdown-Cheatsheet?style=for-the-badge)
```

![GitHub forks](https://img.shields.io/github/forks/lifeparticle/Markdown-Cheatsheet?style=for-the-badge)

# Lists

## Ordered

Mac: <kbd>command+shift+7</kbd>

Windows: <kbd>control+shift+7</kbd>

```md
1. One
2. Two
3. Three
```

1. One
2. Two
3. Three

```md
1. First level
    1. Second level
        - Third level
            - Fourth level
2. First level
    1. Second level
3. First level
    1. Second level
```

1. First level
    1. Second level
        - Third level
            - Fourth level
2. First level
    1. Second level
3. First level
    1. Second level

## Unordered

Mac: <kbd>command+shift+8</kbd>

Windows: <kbd>control+shift+8</kbd>

```md
* 1
* 2
* 3

+ 1
+ 2
+ 3


- 1
- 2
- 3
```

<!-- markdownlint-disable MD004 -->

* 1
* 2
* 3

+ 1
+ 2
+ 3

<!-- markdownlint-enable MD004 -->

- 1
- 2
- 3

```md
- First level
  - Second level
    - Third level
      - Fourth level
- First level
  - Second level
- First level
  - Second level
```

- First level
  - Second level
    - Third level
      - Fourth level
- First level
  - Second level
- First level
  - Second level

```md
<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>
```

<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>

## Task

```md
- [x] Fix Bug 223
- [ ] Add Feature 33
- [ ] Add unit tests
```

- [x] Fix Bug 223
- [ ] Add Feature 33
- [ ] Add unit tests

# Buttons

```md
<kbd>cmd + shift + p</kbd>
```

<kbd>cmd + shift + p</kbd>

```md
<kbd> <br> cmd + shift + p <br> </kbd>
```

<kbd> <br> cmd + shift + p <br> </kbd>

```md
<kbd>[Markdown-Cheatsheet](https://github.com/lifeparticle/Markdown-Cheatsheet)</kbd>
```

<kbd>[Markdown-Cheatsheet](https://github.com/lifeparticle/Markdown-Cheatsheet)</kbd>

```md
[<kbd>Markdown-Cheatsheet</kbd>](https://github.com/lifeparticle/Markdown-Cheatsheet)
```

[<kbd>Markdown-Cheatsheet</kbd>](https://github.com/lifeparticle/Markdown-Cheatsheet)

## Button with emoji

<!-- markdownlint-disable-next-line MD013 -->
<kbd> <br> [Markdown-Cheatsheet](https://github.com/lifeparticle/Markdown-Cheatsheet) ↗️ <br> </kbd>

```md
<kbd> <br> [Markdown-Cheatsheet](https://github.com/lifeparticle/Markdown-Cheatsheet) ↗️ <br> </kbd>
```

# Collapsible items (28 July 2023)

```md
<details>
  <summary>Markdown</summary>

-  <kbd>[Markdown Editor](https://binarytree.dev/me)</kbd>
-  <kbd>[Table Of Content](https://binarytree.dev/toc)</kbd>
-  <kbd>[Markdown Table Generator](https://binarytree.dev/md_table_generator)</kbd>

</details>
```

<details>
  <summary>Markdown</summary>

- <kbd>[Markdown Editor](https://binarytree.dev/me)</kbd>
- <kbd>[Table Of Content](https://binarytree.dev/toc)</kbd>
- <kbd>[Markdown Table Generator](https://binarytree.dev/md_table_generator)</kbd>

</details>

# Horizontal Rule

```md
---
***
___
```

---

<!-- markdownlint-disable-next-line MD035 -->
***

<!-- markdownlint-disable-next-line MD035 -->
___

# Diagrams (19 July 2022)

````md
```mermaid
pie
"Movies" : 80
"TV shows" : 20
```
````

```mermaid
pie
"Movies" : 80
"TV shows" : 20
```

# Mathematical expressions (19 July 2022)

> [!IMPORTANT]
> Check out the official documentation on [GitHub](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions) to learn more about writing and formatting MathJax syntax.

```md
This is an inline math expression $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
```

This is an inline math expression $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$

```md
$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$
```

$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$

# Alerts (8 January 2024)

```md
> [!NOTE]
> Essential details that users should not overlook, even when browsing quickly.

<br>

> [!TIP]
> Additional advice to aid users in achieving better outcomes.

<br>

> [!IMPORTANT]
> Vital information required for users to attain success.

<br>

> [!WARNING]
> Urgent content that requires immediate user focus due to possible risks.

<br>

> [!CAUTION]
> Possible negative outcomes resulting from an action.
```

> [!NOTE]
> Essential details that users should not overlook, even when browsing quickly.

<br>

> [!TIP]
> Additional advice to aid users in achieving better outcomes.

<br>

> [!IMPORTANT]
> Vital information required for users to attain success.

<br>

> [!WARNING]
> Urgent content that requires immediate user focus due to possible risks.

<br>

> [!CAUTION]
> Possible negative outcomes resulting from an action.

# Mention people and teams

In issues:

```md
@lifeparticle
```

[Example shown in issue](https://github.com/lifeparticle/Markdown-Cheatsheet/issues/1)

In markdown file:

```md
https://github.com/lifeparticle
```

https://github.com/lifeparticle

# Reference issues and pull requests

In issues:

```md
#1
#10
```

[Example shown in issue](https://github.com/lifeparticle/Markdown-Cheatsheet/issues/1)

In markdown file:

```md
https://github.com/lifeparticle/Markdown-Cheatsheet/issues/1
https://github.com/lifeparticle/Markdown-Cheatsheet/pull/10
```

https://github.com/lifeparticle/Markdown-Cheatsheet/issues/1

https://github.com/lifeparticle/Markdown-Cheatsheet/pull/10

# Color models

In issues:

```md
`#ffffff`
`#000000`
```

[Example shown in issue](https://github.com/lifeparticle/Markdown-Cheatsheet/issues/1)

![image](https://github.com/user-attachments/assets/523128b8-e877-4e6f-884c-28691eaa1d8f)

# View Code

Click either the Code (top right) or Raw (top left) option to see the markdown code.

<img width="1470" alt="code" src="https://github.com/lifeparticle/Markdown-Cheatsheet/assets/1612112/b70541b0-fce8-4f5e-97f4-6443c20b98ec">

> [!NOTE]
> Make sure you have clicked the markdown file to see the above view.

<img width="907" alt="file" src="https://github.com/lifeparticle/Markdown-Cheatsheet/assets/1612112/a4423154-69de-43c1-aeb5-5348b9f05088">

# Code in titles

In issue, and pull request titles.

`TEST` ISSUE

```md

`TEST` ISSUE

```

<img width="520" alt="Screen Shot 2024-06-05 at 12 11 37 pm" src="https://github.com/lifeparticle/Markdown-Cheatsheet/assets/1612112/33002e7e-e75b-44c8-8585-933df7a1a7a8">

# Reference Labels

Labels referenced by URLs in Markdown are now automatically rendered.

https://github.com/lifeparticle/Markdown-Cheatsheet/labels/documentation

```md
https://github.com/lifeparticle/Markdown-Cheatsheet/labels/documentation
```

# Miscellaneous

## Comments

<!--
Lorem ipsum dolor sit amet
-->

```md
<!--
Lorem ipsum dolor sit amet
-->
```

## Escaping Markdown Characters

- **Before escaping**

```md
* Asterisk
\ Backslash
` Backtick
{} Curly braces
. Dot
! Exclamation mark
# Hash symbol

- Hyphen symbol

() Parentheses

+ Plus symbol

[] Square brackets
_ Underscore`
```

* Asterisk <!-- markdownlint-disable-line MD004 -->
\ Backslash
` Backtick
{} Curly braces
. Dot
! Exclamation mark
<!-- omit in toc -->
# Hash symbol <!-- markdownlint-disable-line MD022 -->

- Hyphen symbol

() Parentheses

+ Plus symbol <!-- markdownlint-disable-line MD004 -->

[] Square brackets
_ Underscore

- **After escaping**

```md
\* Asterisk
\\ Backslash
\` Backtick
\{} Curly braces
\. Dot
\! Exclamation mark
\# Hash symbol
\- Hyphen symbol
\() Parentheses
\+ Plus symbol
\[] Square brackets
\_ Underscore
```

\* Asterisk
\\ Backslash
\` Backtick
\{} Curly braces
\. Dot
\! Exclamation mark
\# Hash symbol
\- Hyphen symbol
\() Parentheses
\+ Plus symbol
\[] Square brackets
\_ Underscore

## Emojis

```md
:octocat:
```

:octocat:

[Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908)

## Line break

<!-- markdownlint-disable-next-line MD038 -->
You can use `<br>` to insert a single line break. Make sure to use an em space ` `. For example:

```md
<table><tr><td> <br> The quick brown fox jumps over the lazy dog. <br> </td></tr></table>
```

<table><tr><td> <br> The
 quick brown fox jumps over the lazy
  dog. <br> </td></tr></table>

Or

```md
<table><tr><td> <br><br><br> The quick brown fox jumps over the lazy dog. <br><br><br> </td></tr></table>
```

<table><tr><td> <br><br><br> The
 quick brown fox jumps over the lazy
  dog. <br><br><br> </td></tr></table>

## Back to top

First place the following code at start of your markdown file

```md
<a name="top"></a>
```

Then use one of the following code at the place you want to return to top.

[Back to top](#top)

[:arrow_up:](#top)

```md
[Back to top](#top)

[:arrow_up:](#top)
```

# Bitbucket

Bitbucket Supported Markdown for [READMEs](https://confluence.atlassian.com/bitbucketserver/markdown-syntax-guide-776639995.html). Also, create a [table of contents](https://support.atlassian.com/bitbucket-cloud/docs/add-a-table-of-contents-to-a-wiki/).

# Azure DevOps Project wiki

Azure DevOps Supported Markdown for [Project wiki](https://learn.microsoft.com/en-us/azure/devops/project/wiki/markdown-guidance?view=azure-devops).

# MDX

You can write JSX in your markdown document using [MDX](https://mdxjs.com/).

# Tools

1. Create a Markdown table of content - [binarytree](https://binarytree.dev/markdown/toc), [github-markdown-toc](https://github.com/ekalinin/github-markdown-toc)
2. Create an empty Markdown table - [Tablesgenerator](https://www.tablesgenerator.com/markdown_tables)
3. Convert Excel to Markdown table - [Tableconvert](https://tableconvert.com/)
4. Markdown preview for Sublime Text 3 - [Packagecontrol](https://packagecontrol.io/packages/MarkdownPreview)
5. Markdown preview Visual Studio Code - [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
6. A collection of awesome markdown goodies - [Awesome Markdown](https://github.com/mundimark/awesome-markdown)
7. Markdownlint - [markdownlint](https://github.com/DavidAnson/markdownlint), [markdownlint-cli2](https://github.com/DavidAnson/markdownlint-cli2), [markdownlint-cli2-action](https://github.com/DavidAnson/markdownlint-cli2-action), [vscode-markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

---

<div align="center">

  This README has been optimized for accessibility based on GitHub's blogpost
  "[Tips for Making your GitHub Profile Page Accessible](https://github.blog/2023-10-26-5-tips-for-making-your-github-profile-page-accessible)".

</div>
