---
title: "hello world"
date: 2023-09-18T07:44:00+07:00
authors: ['Reinaldo Ulian']
tags: ['xx1000']
draft: false
math: true
url: "0048"
---
# first section
Content of first section.
## Complex Diagram

```mermaid
graph LR;

  subgraph A[Start]
    A1[Initialize]
    A2[Input Data]
    A3[Validate Data]
  end

  subgraph B[Main Process]
    B1[Step 1]
    B2[Step 2]
    B3[Step 3]
    B4[Step 4]
  end

  subgraph C[Conditional]
    C1[Condition 1]
    C2[Condition 2]
    C3[Condition 3]
  end

  subgraph D[Output]
    D1[Generate Output]
    D2[Display Output]
  end

  A1 --> A2
  A2 --> A3

  A3 -->|Valid| B1
  A3 -->|Invalid| D1

  B1 --> B2
  B2 --> C1
  B3 --> C2
  B4 --> C3

  C1 --> D1
  C2 --> D1
  C3 --> D2

  D1 -->|Continue| A2
  D1 -->|Finish| E[End]

  D2 -->|Finish| E

## youtube
{{< youtube MCVkMmYL-aY>}}
## Image
![Image Description](https://assets.pikiran-rakyat.com/crop/0x0:0x0/x/photo/2023/02/17/3967434348.png)
## svg
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <circle cx="50" cy="50" r="40" stroke="black" stroke-width="2" fill="transparent">
    <animate attributeName="r" from="40" to="10" dur="2s" begin="0s" repeatCount="indefinite" />
  </circle>
</svg>

## table
no| Tanggal | Kegiatan | Info
:-: | :- | -: | :-:
1 | 22 Jun | Latihan | -
3 | 15 Jul | UTS | $\frac{x}{y}$
4 | 16 Aug | Praktikum| [instagram](https://www.instagram.com)
4 | 31 Aug | UAS | -
4 | 2 Sep | REMEDIAL | **nothing** 


{{< toc >}}
## link

- [Google](https://www.google.com/)
- [GitHub](https://github.com)

## list

+ item
    - dua
    - tiga

+ item lain
+ item lain lagi

## equation

$$
\mathbf{M} =
\left[
\begin{matrix}
1 & 2 & 4 & 5 &5 \newline
1 & 2 & 4 & 5 &5 \newline
1 & 2 & y^2 & z & x \newline
\end {matrix}
\right]
$$

$$
x_{1,2} = \frac{-b \pm \sqrt{b^2 -4ac}}{2a}
$$

$$
\tag{23}
y = ax^2 + bx +c
$$
