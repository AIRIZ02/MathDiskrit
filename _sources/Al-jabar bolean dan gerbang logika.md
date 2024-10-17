---
title: Al-jabar bolean dan gerbang logika

---

Berikut adalah materi tentang Aljabar Boolean dan Gerbang Logika, lengkap dengan contoh rumus dan gambar. 

## Aljabar Boolean

Aljabar Boolean adalah cabang matematika yang berfokus pada variabel yang hanya dapat memiliki dua nilai, yaitu benar (1) dan salah (0). Aljabar ini digunakan dalam logika digital, sistem komputer, dan pengolahan sinyal.

### 1. Operasi Dasar Aljabar Boolean

Ada tiga operasi dasar dalam aljabar Boolean:

1. **AND (Konjungsi)**  
   - Simbol: \( A \cdot B \) atau \( AB \)  
   - Hasil: 1 jika kedua operand bernilai 1; jika tidak, hasilnya 0.
   - Tabel Kebenaran:
     | A | B | A AND B |
     |---|---|---------|
     | 0 | 0 |    0    |
     | 0 | 1 |    0    |
     | 1 | 0 |    0    |
     | 1 | 1 |    1    |

2. **OR (Disjungsi)**  
   - Simbol: \( A + B \)  
   - Hasil: 1 jika salah satu operand bernilai 1; jika kedua operand bernilai 0, hasilnya 0.
   - Tabel Kebenaran:
     | A | B | A OR B |
     |---|---|--------|
     | 0 | 0 |   0    |
     | 0 | 1 |   1    |
     | 1 | 0 |   1    |
     | 1 | 1 |   1    |

3. **NOT (Negasi)**  
   - Simbol: \( \overline{A} \)  
   - Hasil: Mengubah nilai operand; jika operand 1, hasilnya 0, dan sebaliknya.
   - Tabel Kebenaran:
     | A | NOT A |
     |---|-------|
     | 0 |   1   |
     | 1 |   0   |

### 2. Hukum-Hukum Aljabar Boolean

1. **Hukum Identitas**:
   - $( A + 0 = A )$
   - $( A \cdot 1 = A )$

2. **Hukum Dominsi**:
   - $( A + 1 = 1 ) $
   - $( A \cdot 0 = 0 )$

3. **Hukum Idempoten**:
   - $( A + A = A )$
   - $( A \cdot A = A )$

4. **Hukum Komplement**:
   - $( A + \overline{A} = 1 )$
   - $( A \cdot \overline{A} = 0 )$

5. **Hukum Distribusi**:
   - $( A \cdot (B + C) = (A \cdot B) + (A \cdot C) )$
   - $( A + (B \cdot C) = (A + B) \cdot (A + C) )$

Berikut adalah materi tentang Gerbang Logika, lengkap dengan gambar dan daftar pustakanya.

## Gerbang Logika

Gerbang logika adalah komponen dasar dari rangkaian digital yang digunakan untuk melakukan operasi logika pada satu atau lebih input untuk menghasilkan output. Gerbang logika adalah dasar dari semua sistem komputer dan perangkat digital.

### 1. Jenis-jenis Gerbang Logika

Berikut adalah jenis-jenis gerbang logika yang paling umum digunakan:

#### a. Gerbang AND

- **Simbol**: 
  ![Gerbang AND](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/AND_ANSI_Labelled.svg/1200px-AND_ANSI_Labelled.svg.png)
  
- **Fungsi**: Menghasilkan output 1 hanya jika semua input bernilai 1.
  
- **Tabel Kebenaran**:
  | A | B | A AND B |
  |---|---|---------|
  | 0 | 0 |    0    |
  | 0 | 1 |    0    |
  | 1 | 0 |    0    |
  | 1 | 1 |    1    |

#### b. Gerbang OR

- **Simbol**: 
  ![Gerbang OR](https://upload.wikimedia.org/wikipedia/commons/thumb/1/14/OR_ANSI_Labelled.svg/1200px-OR_ANSI_Labelled.svg.png)
  
- **Fungsi**: Menghasilkan output 1 jika salah satu atau lebih input bernilai 1.
  
- **Tabel Kebenaran**:
  | A | B | A OR B |
  |---|---|--------|
  | 0 | 0 |   0    |
  | 0 | 1 |   1    |
  | 1 | 0 |   1    |
  | 1 | 1 |   1    |

#### c. Gerbang NOT

- **Simbol**: 
  ![Gerbang NOT](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/NOT_ANSI_Labelled.svg/1200px-NOT_ANSI_Labelled.svg.png)
  
- **Fungsi**: Menghasilkan output yang merupakan negasi dari input. Jika input 1, output 0, dan sebaliknya.
  
- **Tabel Kebenaran**:
  | A | NOT A |
  |---|-------|
  | 0 |   1   |
  | 1 |   0   |

#### d. Gerbang NAND

- **Simbol**: 
  ![Gerbang NAND](https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NAND_ANSI_Labelled.svg/1200px-NAND_ANSI_Labelled.svg.png)
  
- **Fungsi**: Menghasilkan output 0 hanya jika semua input bernilai 1 (negasi dari AND).
  
- **Tabel Kebenaran**:
  | A | B | A NAND B |
  |---|---|----------|
  | 0 | 0 |    1     |
  | 0 | 1 |    1     |
  | 1 | 0 |    1     |
  | 1 | 1 |    0     |

#### e. Gerbang NOR

- **Simbol**: 
  ![Gerbang NOR](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/NOR_ANSI_Labelled.svg/1200px-NOR_ANSI_Labelled.svg.png)
  
- **Fungsi**: Menghasilkan output 1 hanya jika semua input bernilai 0 (negasi dari OR).
  
- **Tabel Kebenaran**:
  | A | B | A NOR B |
  |---|---|---------|
  | 0 | 0 |    1    |
  | 0 | 1 |    0    |
  | 1 | 0 |    0    |
  | 1 | 1 |    0    |

#### f. Gerbang XOR (Exclusive OR)

- **Simbol**: 
  ![Gerbang XOR](https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/XOR_ANSI_Labelled.svg/1200px-XOR_ANSI_Labelled.svg.png)
  
- **Fungsi**: Menghasilkan output 1 jika jumlah input yang bernilai 1 adalah ganjil.
  
- **Tabel Kebenaran**:
  | A | B | A XOR B |
  |---|---|---------|
  | 0 | 0 |    0    |
  | 0 | 1 |    1    |
  | 1 | 0 |    1    |
  | 1 | 1 |    0    |

### 2. Penerapan Gerbang Logika

Gerbang logika digunakan dalam berbagai aplikasi, termasuk:

- **Rangkaian Digital**: Untuk membangun rangkaian logika seperti penambah, pengurang, dan rangkaian kontrol.
- **Sistem Komputer**: Untuk mengatur pengolahan data dan kontrol alur program.
- **Sistem Kontrol Otomatis**: Digunakan dalam pengendalian sistem industri dan otomatisasi.

### 3. Rangkaian Contoh

Sebagai contoh, berikut adalah rangkaian yang menggunakan beberapa gerbang logika:

- **Rangkaian Penjumlah 1-bit**:
  - Menggunakan gerbang XOR untuk menghasilkan jumlah dan gerbang AND untuk menghasilkan carry.
  
  ![Rangkaian Penjumlah 1-bit](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/1-bit_full_adder.svg/1200px-1-bit_full_adder.svg.png)
### 4. Contoh Penerapan

Misalkan kita memiliki dua variabel logika, A dan B. Kita ingin membuat suatu ekspresi logika yang menggunakan operasi AND dan OR:

**Ekspresi:** $( F = A \cdot B + \overline{A} )$

- Tabel Kebenaran untuk ekspresi di atas:

| A | B | $( \overline{A} )$ | $( A \cdot B )$ | $( F = A \cdot B + \overline{A} )$ |
|---|---|-----------------|-----------------|-----------------------------------|
| 0 | 0 |        1        |        0        |                 1                 |
| 0 | 1 |        1        |        0        |                 1                 |
| 1 | 0 |        0        |        0        |                 0                 |
| 1 | 1 |        0        |        1        |                 1                 |

## Daftar Pustaka

1. Morris Mano, "Digital Design," 5th Edition. Pearson, 2013.
2. John F. Wakerly, "Digital Design: Principles and Practices," 4th Edition. Prentice Hall, 2005.
3. Charles H. Roth Jr., "Fundamentals of Logic Design," 7th Edition. Cengage Learning, 2014