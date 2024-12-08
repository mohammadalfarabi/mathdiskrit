---
title: Probabilitas bayes

---

# Teorema Bayes

Teorema Bayes adalah aturan dalam probabilitas yang menggambarkan cara memperbarui kemungkinan suatu hipotesis berdasarkan bukti baru. Teorema ini dinamai setelah Thomas Bayes, seorang matematikawan Inggris.

## Rumus Umum Teorema Bayes:
$P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}$

- **\(P(A|B)\)**: Probabilitas kejadian **A** terjadi jika **B** telah terjadi (probabilitas posterior). 
- **\(P(B|A)\)**: Probabilitas **B** terjadi jika **A** terjadi (probabilitas likelihood). 
- **\(P(A)\)**: Probabilitas awal atau sebelum bukti, disebut probabilitas prior. 
- **\(P(B)\)**: Probabilitas total dari **B**, yang dapat dihitung sebagai:
  $P(B) = P(B|A) \cdot P(A) + P(B|\neg A) \cdot P(\neg A)$

Berikut adalah penjelasan tentang **Posterior**, **Prior**, dan **Likelihood** dalam konteks **Teorema Bayes**:



### **1. Prior**
- **Definisi**: Prior adalah probabilitas awal dari suatu hipotesis sebelum memperhitungkan bukti baru.
- **Notasi**: $(P(A))$, di mana $(A)$ adalah hipotesis.
- **Makna**: Ini mencerminkan pengetahuan atau asumsi awal kita tentang suatu kejadian. Misalnya:
  - Probabilitas awal seseorang memiliki penyakit sebelum melihat hasil tes.


### **2. Likelihood**
- **Definisi**: Likelihood adalah probabilitas bukti terjadi **dengan asumsi hipotesis benar**.
- **Notasi**: $(P(B|A))$, di mana $(B)$ adalah bukti, dan $(A)$ adalah hipotesis.
- **Makna**: Likelihood menunjukkan seberapa mungkin bukti $(B)$ terjadi jika hipotesis $(A)$ benar. Misalnya:
  - Probabilitas tes menunjukkan hasil positif jika seseorang benar-benar sakit.


### **3. Posterior**
- **Definisi**: Posterior adalah probabilitas diperbarui dari hipotesis setelah memperhitungkan bukti baru.
- **Notasi**: $(P(A|B))$, di mana $(A)$ adalah hipotesis, dan $(B)$ adalah bukti.
- **Makna**: Ini adalah probabilitas yang telah diperbarui dengan bukti baru. Misalnya:
  - Probabilitas seseorang memiliki penyakit berdasarkan hasil tes yang positif.

### **Hubungan dengan Teorema Bayes**
Teorema Bayes menggambarkan hubungan antara prior, likelihood, dan posterior:
$P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}$

- **Prior**: $(P(A))$
- **Likelihood**: $(P(B|A))$
- **Posterior**: $(P(A|B))$
- **Normalisasi (probabilitas total)**: $(P(B))$


