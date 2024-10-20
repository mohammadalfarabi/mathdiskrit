---
title: Boolean

---

# Aljabar Boolean Dan Gerbang Logika
**Boolean** mengacu pada **logika boolean**, yang merupakan cabang dari aljabar logika yang hanya beroperasi dengan dua nilai: **benar (true)** dan **salah (false)**. Konsep ini pertama kali dikembangkan oleh George Boole, dan digunakan untuk operasi logika biner dalam sistem komputer, teori himpunan, dan struktur logika lainnya.

Beberapa operasi dasar dalam logika boolean meliputi:

1. **AND (∧)**
   - Hanya benar jika kedua operan bernilai benar.
   - Contoh: $( A \land B )$ benar hanya jika **A** dan **B** keduanya benar.
   
2. **OR (∨)**
   - Benar jika salah satu atau kedua operan bernilai benar.
   - Contoh: $( A \lor B )$ benar jika **A** atau **B** (atau keduanya) benar.
   
3. **NOT (¬)**
   - Membalikkan nilai kebenaran.
   - Contoh: $( \neg A )$ bernilai benar jika **A** salah, dan sebaliknya.
   
4. **IMPLIKASI (→)**
   - Bernilai salah hanya jika premis (sebelum panah) benar dan konklusi (setelah panah) salah.
   - Contoh: $( A \rightarrow B )$ benar kecuali **A** benar dan **B** salah.

Tabel kebenaran (truth table) sering digunakan untuk memvisualisasikan hasil dari operasi boolean ini. Berikut adalah contoh tabel kebenaran untuk operasi AND dan OR:

| A   | B   | A ∧ B | A ∨ B |
|-----|-----|-------|-------|
| T   | T   |   T   |   T   |
| T   | F   |   F   |   T   |
| F   | T   |   F   |   T   |
| F   | F   |   F   |   F   |

Operasi boolean sangat penting dalam **matematika diskret** karena digunakan dalam berbagai topik, seperti:
- **Teori himpunan** (operasi antara himpunan)
- **Logika proposisional** (analisis pernyataan logika)
- **Algoritma** dan **struktur data** (seperti pencarian dan pengurutan)

Konsep ini juga mendasari **gerbang logika** dalam rangkaian digital yang mengontrol perilaku sirkuit elektronik dalam komputer.


#Gerbang logika 
Gerbang Logika adalah blok dasar dalam sirkuit digital yang digunakan untuk melakukan operasi logika. Gerbang-gerbang ini menerima satu atau lebih sinyal input dan menghasilkan satu sinyal output berdasarkan fungsi logika tertentu. Setiap gerbang logika mewakili operasi dasar dalam aljabar Boolean. Berikut beberapa jenis gerbang logika dasar:

1. **Gerbang AND**: Menghasilkan output **TRUE (1)** hanya jika semua inputnya **TRUE (1)**.
   - Simbol: $( A \cdot B )$
   - Tabel kebenaran:
     | A | B | Output |
     |---|---|--------|
     | 0 | 0 |   0    |
     | 0 | 1 |   0    |
     | 1 | 0 |   0    |
     | 1 | 1 |   1    |

2. **Gerbang OR**: Menghasilkan output **TRUE (1)** jika salah satu input atau lebih adalah **TRUE (1)**.
   - Simbol: $( A + B )$
   - Tabel kebenaran:
     | A | B | Output |
     |---|---|--------|
     | 0 | 0 |   0    |
     | 0 | 1 |   1    |
     | 1 | 0 |   1    |
     | 1 | 1 |   1    |

3. **Gerbang NOT**: Menghasilkan output yang merupakan kebalikan dari inputnya (mengubah **TRUE** menjadi **FALSE** dan sebaliknya).
   - Simbol: $( \overline{A} )$
   - Tabel kebenaran:
     | A | Output |
     |---|--------|
     | 0 |    1   |
     | 1 |    0   |

4. **Gerbang NAND**: Kombinasi dari gerbang AND yang diikuti oleh gerbang NOT. Menghasilkan output **FALSE (0)** hanya jika semua inputnya **TRUE (1)**.
   - Simbol: $( \overline{A \cdot B} )$
   - Tabel kebenaran:
     | A | B | Output |
     |---|---|--------|
     | 0 | 0 |   1    |
     | 0 | 1 |   1    |
     | 1 | 0 |   1    |
     | 1 | 1 |   0    |

5. **Gerbang NOR**: Kombinasi dari gerbang OR yang diikuti oleh gerbang NOT. Menghasilkan output **TRUE (1)** hanya jika semua inputnya **FALSE (0)**.
   - Simbol: $( \overline{A + B} )$
   - Tabel kebenaran:
     | A | B | Output |
     |---|---|--------|
     | 0 | 0 |   1    |
     | 0 | 1 |   0    |
     | 1 | 0 |   0    |
     | 1 | 1 |   0    |

6. **Gerbang XOR (Exclusive OR)**: Menghasilkan output **TRUE (1)** hanya jika satu dari inputnya **TRUE (1)**, tetapi tidak keduanya.
   - Simbol: $( A \oplus B )$
   - Tabel kebenaran:
     | A | B | Output |
     |---|---|--------|
     | 0 | 0 |   0    |
     | 0 | 1 |   1    |
     | 1 | 0 |   1    |
     | 1 | 1 |   0    |

7. **Gerbang XNOR (Exclusive NOR)**: Kebalikan dari gerbang XOR, menghasilkan output **TRUE (1)** jika inputnya sama.
   - Simbol: $( \overline{A \oplus B} )$
   - Tabel kebenaran:
     | A | B | Output |
     |---|---|--------|
     | 0 | 0 |   1    |
     | 0 | 1 |   0    |
     | 1 | 0 |   0    |
     | 1 | 1 |   1    |

Gerbang logika digunakan dalam berbagai aplikasi seperti rangkaian komputer, pemrosesan sinyal, dan perangkat digital lainnya.