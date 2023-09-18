---
title: "PEMBUATAN WEB"
date: 2023-09-18T07:44:00+07:00
authors: ['Reinaldo Ulian']
tags: ['xx1000']
draft: false
math: true
url: "0048"
---
# first section
Selamat datang dalam panduan lengkap pembuatan website! Apakah Anda ingin membuat website pribadi, blog, portfolio, atau bahkan situs web bisnis, panduan ini akan membimbing Anda melalui langkah-langkah esensial yang dibutuhkan.

Pembuatan website adalah proses yang kreatif dan memuaskan yang memungkinkan Anda untuk mengekspresikan diri Anda secara online. Dengan kemajuan teknologi, sekarang lebih mudah daripada sebelumnya untuk memulai.

## Diagram Pembuatan web
<
<canvas id="myChart" width="400" height="400"></canvas>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  var ctx = document.getElementById('myChart').getContext('2d');
  var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['Identifikasi Kebutuhan', 'Perencanaan', 'Desain', 'Pengembangan', 'Pengujian', 'Peluncuran'],
      datasets: [{
        label: 'Langkah',
        data: [1, 2, 3, 4, 5, 6],
        backgroundColor: [
          'rgba(75, 192, 192, 0.2)',
          'rgba(75, 192, 192, 0.2)',
          'rgba(75, 192, 192, 0.2)',
          'rgba(75, 192, 192, 0.2)',
          'rgba(75, 192, 192, 0.2)',
          'rgba(75, 192, 192, 0.2)'
        ],
        borderColor: [
          'rgba(75, 192, 192, 1)',
          'rgba(75, 192, 192, 1)',
          'rgba(75, 192, 192, 1)',
          'rgba(75, 192, 192, 1)',
          'rgba(75, 192, 192, 1)',
          'rgba(75, 192, 192, 1)'
        ],
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true,
          stepSize: 1,
          title: {
            display: true,
            text: 'Langkah'
          }
        }
      }
    }
  });
</script>

## Diagram

{{< mermaid >}}
flowchart LR
  B(("Perencanaan"))
  I[/"Desain"/]
  P[/"Pengembangan"/]
  O[/"Pengujian"/]
  E(("End"))
  B --> I
  I --> P
  P --> O
  O --> E
{{< /mermaid >}}

## youtube
{{< youtube MCVkMmYL-aY>}}
## Image
![Image Description](https://assets.pikiran-rakyat.com/crop/0x0:0x0/x/photo/2023/02/17/3967434348.png)
## Animation with SVG

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

## Complex SVG with Styled Rect

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

<!-- 
## table
no| Tanggal | Kegiatan | Info
:-: | :- | -: | :-:
1 | 22 Jun | Latihan | -
3 | 15 Jul | UTS | $\frac{x}{y}$
4 | 16 Aug | Praktikum| [instagram](https://www.instagram.com)
4 | 31 Aug | UAS | -
4 | 2 Sep | REMEDIAL | **nothing** 
 -->


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
