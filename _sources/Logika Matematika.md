   ---
title: Logika Matematika

---

# Logika Matematika

## Nagasi
Negasi dalam matematika adalah operasi logika yang membalikkan nilai kebenaran dari suatu pernyataan. Jika suatu pernyataan bernilai benar, maka negasinya akan bernilai salah, dan sebaliknya. Secara umum, jika pernyataan $\ p$ bernilai benar, maka negasi dari $\ p$ (dilambangkan dengan $\neg P$  bernilai salah.

### Notasi Negasi

Jika $\ p$ adalah suatu pernyataan, maka negasi dari $\ p$ dinyatakan sebagai:
$$
\neg P
$$

### Contoh

Misalkan $\ p$ adalah pernyataan:
- $\ p$ : "Angka 5 adalah bilangan prima."

Karena pernyataan ini benar, maka negasi dari $\ P$, yaitu $\neg P$, adalah:
- $\neg P$ : "Angka 5 bukan bilangan prima."

Negasi dari pernyataan benar menjadi salah, dan sebaliknya. Secara logika:

$$
P = \text{benar} \quad \Rightarrow \quad \neg P = \text{salah}
$$

Atau dalam bentuk tabel kebenaran:

|  $P$  | $\neg P$ |
|:-----:|:--------:|
| $True$  |  $False$   |
| $False$ |   $True$   |


## Konjungsi
Konjungsi adalah operasi logika yang menggabungkan dua proposisi dan menghasilkan nilai benar hanya jika kedua proposisi tersebut benar. Dalam notasi, konjungsi biasanya dilambangkan dengan simbol "$\land$". 

### Notasi Konjungsi

Jika $P$ dan $Q$ adalah dua pernyataan, maka konjungsi dari $P$ dan $Q$ dinyatakan sebagai:
$$
P \land Q
$$
Konjungsi $P \land Q$ akan bernilai *benar* hanya jika kedua pernyataan $P$ dan $Q$ benar.

### Contoh

Misalkan:
- $P$: "Angka 4 adalah bilangan genap."
- $Q$: "Angka 4 lebih kecil dari 10."

Pernyataan $P$ dan $Q$ keduanya benar, sehingga konjungsi $P \land Q$ juga bernilai benar:
- $P \land Q$: "Angka 4 adalah bilangan genap *dan* angka 4 lebih kecil dari 10."

### Tabel Kebenaran Konjungsi

Tabel kebenaran konjungsi untuk dua pernyataan $P$ dan $Q$ adalah sebagai berikut:


|   $P$   | $Q$     | $P \land Q$ |
|:-------:| ------- |:-----------:|
| $True$  | $True$  |   $True$    |
| $True$  | $False$ |   $False$   |
| $False$ | $True$  |   $False$   |
| $False$ | $False$ |   $False$   |



Dalam tabel ini, konjungsi $P \land Q$ hanya bernilai *benar* ketika kedua pernyataan $P$ dan $Q$ bernilai benar.


## Disjungsi
Disjungsi adalah operasi logika yang menggabungkan dua proposisi dan menghasilkan nilai benar jika setidaknya satu dari proposisi tersebut benar. Disjungsi dilambangkan dengan simbol "$\lor$".

### Notasi Disjungsi

Jika $P$ dan $Q$ adalah dua pernyataan, maka disjungsi dari $P$ dan $Q$ dinyatakan sebagai:
$$
P \lor Q
$$
Disjungsi $P \lor Q$ akan bernilai *benar* jika salah satu dari pernyataan $P$ atau $Q$ benar, atau keduanya benar.

### Contoh

Misalkan:
- $P$: "Angka 4 adalah bilangan genap."
- $Q$: "Angka 4 lebih besar dari 10."

Pernyataan $P$ benar, sedangkan $Q$ salah. Namun, disjungsi $P \lor Q$ tetap bernilai benar karena salah satu pernyataan, yaitu $P$, bernilai benar:
- $P \lor Q$: "Angka 4 adalah bilangan genap *atau* angka 4 lebih besar dari 10."

### Tabel Kebenaran Disjungsi

Tabel kebenaran disjungsi untuk dua pernyataan $P$ dan $Q$ adalah sebagai berikut:



| $P$     | $Q$     | $P \lor Q$ |
| ------- | ------- |:----------:|
| $True$  | $True$  |   $True$   |
| $True$  | $False$ |   $True$   |
| $False$ | $True$  |   $True$   |
| $False$ | $False$ |  $False$   |

Dalam tabel ini, disjungsi $P \lor Q$ hanya bernilai *salah* ketika kedua pernyataan $P$ dan $Q$ bernilai salah.

## Implikasi

Implikasi adalah operasi logika yang menunjukkan hubungan antara dua proposisi, di mana jika proposisi pertama ($P$) benar, maka proposisi kedua ($Q$) juga harus benar. Implikasi dilambangkan dengan simbol "$\rightarrow$".

### Notasi Implikasi

Jika $P$ dan $Q$ adalah dua pernyataan, maka implikasi dari $P$ dan $Q$ dinyatakan sebagai:
$$
P \rightarrow Q
$$
Pernyataan ini dibaca: "Jika $P$, maka $Q$". Artinya, jika $P$ benar, maka $Q$ harus benar agar implikasi tetap benar.

### Contoh

Misalkan:
- $P$: "Angka 4 adalah bilangan genap."
- $Q$: "Angka 4 lebih kecil dari 10."

Implikasi $P \rightarrow Q$ akan bernilai *benar* karena $P$ benar dan $Q$ juga benar:
- $P \rightarrow Q$: "Jika angka 4 adalah bilangan genap, maka angka 4 lebih kecil dari 10."

### Tabel Kebenaran Implikasi

Tabel kebenaran implikasi untuk dua pernyataan $P$ dan $Q$ adalah sebagai berikut:



| $P$     |   $Q$   | $P \rightarrow Q$ |
| ------- |:-------:| ----------------- |
| $True$  | $True$  | $True$            |
| $True$  | $False$ | $False$           |
| $False$ | $True$  | $True$            |
| $False$ | $False$ | $True$            |

Dalam tabel ini, implikasi $P \rightarrow Q$ hanya bernilai *salah* ketika $P$ benar dan $Q$ salah.

## Biimplikasi

Biimplikasi adalah operasi logika yang menunjukkan bahwa dua proposisi saling mempengaruhi, yaitu keduanya benar atau keduanya salah. Biimplikasi dilambangkan dengan simbol "$\leftrightarrow$".

### Notasi Biimplikasi

Jika $P$ dan $Q$ adalah dua pernyataan, maka biimplikasi dari $P$ dan $Q$ dinyatakan sebagai:
$$
P \leftrightarrow Q
$$
Pernyataan ini dibaca: "$P$ jika dan hanya jika $Q$". Artinya, $P$ benar jika $Q$ benar, dan $P$ salah jika $Q$ salah.

### Contoh

Misalkan:
- $P$: "Angka 4 adalah bilangan genap."
- $Q$: "Angka 4 lebih kecil dari 10."

Kedua pernyataan ini benar, sehingga biimplikasi $P \leftrightarrow Q$ juga bernilai benar:
- $P \leftrightarrow Q$: "Angka 4 adalah bilangan genap *jika dan hanya jika* angka 4 lebih kecil dari 10."

### Tabel Kebenaran Biimplikasi

Tabel kebenaran biimplikasi untuk dua pernyataan $P$ dan $Q$ adalah sebagai berikut:


| $P$     |   $Q$   | $P \leftrightarrow Q$ |
| ------- |:-------:| --------------------- |
| $True$  | $True$  | $True$                |
| $True$  | $False$ | $False$               |
| $False$ | $True$  | $False$               |
| $False$ | $False$ | $True$                |

Dalam tabel ini, biimplikasi $P \leftrightarrow Q$ bernilai *benar* ketika $P$ dan $Q$ memiliki nilai kebenaran yang sama (baik keduanya benar maupun keduanya salah).

## Soal : 
Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$
\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{-}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{-}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{-}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{-}&\text{T}&\text{T}&\end{array}
$$