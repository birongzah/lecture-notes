---
title: "PEMBUATAN WEB"
date: 2023-09-18T07:44:00+07:00
authors: ['Reinaldo Ulian']
tags: ['xx1000']
draft: false
math: true
url: "0048"
---
# Intro
Selamat datang di website saya, saya akan meberitahu anda bagaimana kehidupan sehari-hari sebagai bodybuilder, dan juga bagaimana cara menjadi bodybuilder
## Media Sosial
+ [GitHub](https://birongzah.github.io/lecture-notes/)
+ [Instagram](https://www.Instagram.com)
+ [Twitter](https://www.Twitter.com)

## 5 TAHAPAN

{{< mermaid >}}
flowchart LR
  B(("Memulai Program"))
  I[/"MencukupiNutrisi"/]
  P[/"LatihanInti"/]
  O[/"Recovery"/]
  E(("AchieveGoals"))
  B --> I
  I --> P
  P --> O
  O --> E
{{< /mermaid >}}

## youtube
{{< youtube o9zCgPtsups}}
## Image
![Image Description](https://images8.alphacoders.com/570/570996.jpg)
## contoh markdown
> Ini adalah paragraf kutipan. Ini adalah teks dalam kutipan yang Anda ingin tampilkan.
## contoh tabel
| Nutrisi     | Pagi        | Siang       | Malam       |
|-------------|-------------|-------------|-------------|
| Creatine    | 5 gram      | -           | 5 gram      |
| Protein     | 30 gram     | 40 gram     | 30 gram     |
| BCAA        | -           | 10 gram     | -           |


##
## Berat Badan

Berikut merupakan perkembangan berat badan Saya dari bulan Juni hingga sekarang.
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['Bulan Juni', 'Bulan Juli', 'Bulan Agustus', 'Bulan September'],
        datasets: [{
            label: 'Berat Badan 4 Bulan Terakhir',
            data: [68,69,70,71],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}

## CONTOH ANIMASI SVG

{{< html >}}
<svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with animation -->
  <rect x="10" y="10" width="50" height="50" fill="blue">
    <animate attributeName="width" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="height" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="fill" values="blue;red;green;blue" dur="4s" begin="0s" repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}

## CONTOH SVG LAIN
{{< html >}}
<svg width="400" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with gradients -->
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgb(255,0,0);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgb(0,0,255);stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <rect x="20" y="20" width="200" height="100" fill="url(#grad1)" stroke="green" stroke-width="3" />
  
  <!-- Text element -->
  <text x="30" y="160" font-family="Arial" font-size="24" fill="black">Complex SVG</text>
  
  <!-- Circle with animation -->
  <circle cx="250" cy="150" r="20" fill="orange">
    <animate attributeName="r" from="20" to="50" dur="2s" begin="0s" repeatCount="indefinite" />
  </circle>
</svg>
{{< /html >}}


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
