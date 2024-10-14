---
title: Boolean

---

# Aljabar Boolean Dan Gerbang Logika
**Boolean** mengacu pada **logika boolean**, yang merupakan cabang dari aljabar logika yang hanya beroperasi dengan dua nilai: **benar (true)** dan **salah (false)**. Konsep ini pertama kali dikembangkan oleh George Boole, dan digunakan untuk operasi logika biner dalam sistem komputer, teori himpunan, dan struktur logika lainnya.

Beberapa operasi dasar dalam logika boolean meliputi:

1. **AND (∧)**
   - Hanya benar jika kedua operan bernilai benar.
   - Contoh: \( A \land B \) benar hanya jika **A** dan **B** keduanya benar.
   
2. **OR (∨)**
   - Benar jika salah satu atau kedua operan bernilai benar.
   - Contoh: \( A \lor B \) benar jika **A** atau **B** (atau keduanya) benar.
   
3. **NOT (¬)**
   - Membalikkan nilai kebenaran.
   - Contoh: \( \neg A \) bernilai benar jika **A** salah, dan sebaliknya.
   
4. **IMPLIKASI (→)**
   - Bernilai salah hanya jika premis (sebelum panah) benar dan konklusi (setelah panah) salah.
   - Contoh: \( A \rightarrow B \) benar kecuali **A** benar dan **B** salah.

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
