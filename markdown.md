[TOC]
## Heading
Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:
```
# This is an H1

## This is an H2

###### This is an H6
```

## Font
```
*Italic* or _Italic_
**Bold**
***Bold & Ttalic***
~~Strikethrough~~
++Underline++
==Backgroud highlight==
```
*Italic* or _Italic_  
**Bold**  
***Bold & Ttalic***  
~~Strikethrough~~  
++Underline++  
==Backgroud highlight==

## List
Markdown supports ordered (numbered) and unordered (bulleted) lists.  
Unordered lists use asterisks, pluses, and hyphens — interchangably — as list markers:
*   Red
*   Green
*   Blue  

```
*   Red
*   Green
*   Blue
```

is equivalent to:
```
+   Red
+   Green
+   Blue
```
and 
```
-   Red
-   Green
-   Blue
```
Ordered lists use numbers followed by periods:
```
1.  Bird
2.  McHale
3.  Parish
```

## Table
```
header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2
```
header 1 | header 2  
---|---  
row 1 col 1 | row 1 col 2  
row 2 col 1 | row 2 col 2  

## Align
```
<center>行中心对齐</center>
<p align="left">行左对齐</p>
<p align="right">行右对齐</p>
```
output:
<center>行中心对齐</center>
<p align="left">行左对齐</p>
<p align="right">行右对齐</p>

## Line break
由于markdown编辑器的不同,可能在一行字后面，直接换行回车，也能实现换行，但是在Visual Studio Code上，想要换行必须得在一行字后面空两个格子才行。

## Code
Use six `s to contain code.   
input：
```
、、、
include <stdio.h>
int main(void)
{
printf("Hello world\n");
}
、、、
```
output：
```
include <stdio.h>
int main(void)
{
printf("Hello world\n");
}
```

## Task List
```
- [] incomplete task 1
- [] incomplete task 2
- [x] complete task 1
- [x] complete task 2
```

## Link

## Image

## Sequence Diagram

```
sequenceDiagram
A->>B: How are you?
B->>A: Great!
```

