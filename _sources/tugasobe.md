## Penyelesaian Sistem Persamaan Linier
### Operasi Baris Elementer

### Eliminasi Gauss

Contoh Soal 1 :
Selesaikan dengan eliminasi Gauss

$$
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_3+x_2&=2
\end{array}
$$

Penyelesaian :
$$
\begin{bmatrix}
1&2&3&|6\\
0&0&0&|0\\
0&1&1&|2
\end{bmatrix}
$$

- Tukar baris kedua dan ketiga untuk mendapatkan pivot lebih baik : 

$$
\begin{bmatrix}
1&2&3&|6\\
0&1&1&|2\\
0&0&0&|0
\end{bmatrix}
$$

- Solusi Akhir
$$
\begin{aligned}
x_1&=2-t\\
x_2&=2-t\\
x_3&=t
\end{aligned}
$$

- Jadi, solusi umum dari sistem persamaan adalah:
$$
[(x_1,x_2,x_3)=(2-t,2-t,t), \quad t \in \mathbb{R}]
$$
- Karena ada parameter bebas 𝑡, sistem ini memiliki banyak solusi.

Contoh Soal 2 :
Selesaikan dengan eliminasi Gauss

$$
\begin{array}{cc}
x_1+x_2+x_3&=3\\
2x_1+x_3&=5\\
x_1+2x_2&=2
\end{array}
$$

Contoh Soal 3 :
Selesaikan dengan eliminasi Gauss

$$
\begin{array}{cc}
2x_1+2x_2&=4\\
x_1+x_2&=2\\
\end{array}
$$

Contoh Soal 4 :
Selesaikan dengan eliminasi Gauss

$$
\begin{array}{cc}
x_1+x_2&=5\\
x_1+2x_3&=6\\
\end{array}
$$

