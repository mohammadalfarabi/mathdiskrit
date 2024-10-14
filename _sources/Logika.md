---
title: Logika

---

# Logika Matemaktika 

## Negasi
Negasi adalah proses menyatakan bahwa sesuatu tidak benar atau tidak ada. Dalam logika, ini digunakan untuk membantah proposisi atau pernyataan.

| ( P )  | ( $\neg P$ ) |
|--------|--------------|
| Benar  | Salah        |
| Salah  | Benar        |

https://en.wikipedia.org/wiki/Negation

## Konjungsi
Konjungsi adalah operasi logika yang menghubungkan dua pernyataan dan menghasilkan nilai benar hanya jika kedua pernyataan tersebut benar. Simbol konjungsi dituliskan sebagai ( $P \land Q$ ), Artinya "P dan Q". 

|( P ) |( Q ) |( $P \land Q$ )|
|------|------|---------------|
| Benar| Benar| Benar         |
| Benar| Salah| Salah         |
| Salah| Benar| Salah         |
| Salah| Salah| Salah         |



## Dijungsi
Dijungsi adalah operasi logika yang menghubungkan dua pernyataan dan menghasilkan nilai benar jika setidaknya salah satu dari pernyataan tersebut benar. Simbol dijungsi ditulis sebagai ( $P \lor Q$ ), Artinya "P atau Q". 

| ( P )  | ( Q )  | ( $P \lor Q$ ) |
|--------|--------|----------------|
| Benar  | Benar  | Benar          |
| Benar  | Salah  | Benar          |
| Salah  | Benar  | Benar          |
| Salah  | Salah  | Salah          |

## implikasi
Implikasi adalah operasi logika yang menghubungkan dua pernyataan, biasanya ditulis sebagai ( $P \rightarrow Q$ ). Artinya "Jika P, maka Q".

- Jika P benar dan Q juga benar, maka implikasinya benar.
- Jika P benar tetapi Q salah, maka implikasinya salah.
- Jika P salah, maka implikasinya selalu benar, terlepas dari nilai Q.

| ( P )  | ( Q )  | ( $P \rightarrow Q$ ) |
|--------|--------|-----------------------|
| Benar  | Benar  | Benar                 |
| Benar  | Salah  | Salah                 |
| Salah  | Benar  | Benar                 |
| Salah  | Salah  | Benar                 |

## Biimplikasi
Biimplikasi adalah operasi logika yang menyatakan bahwa dua pernyataan saling mengimplikasikan satu sama lain. Dalam simbol, biimplikasi ditulis sebagai ( $P \leftrightarrow Q$ ), yang berarti "P jika dan hanya jika Q". Ini akan benar jika kedua pernyataan memiliki nilai kebenaran yang sama (baik benar atau salah).

| ( P )  | ( Q )  | ( $P \leftrightarrow Q$ ) |
|--------|--------|---------------------------|
| Benar  | Benar  | Benar                     |
| Benar  | Salah  | Salah                     |
| Salah  | Benar  | Salah                     |
| Salah  | Salah  | Benar                     |


Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{}\end{array}$$