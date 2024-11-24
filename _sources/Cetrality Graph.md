---
title: Cetrality Graph

---

# Cetrality Graph

# Social Network Analysis 
SNA adalah metode untuk mempelajari struktur hubungan atau interaksi antar individu, kelompok, organisasi, atau entitas lainnya dalam sebuah jaringan. SNA memanfaatkan konsep matematika, khususnya teori graf, untuk merepresentasikan hubungan tersebut sebagai simpul (nodes) dan hubungan di antara mereka sebagai sisi (edges).

# Definisi
Centrality: Ukuran matematis yang digunakan untuk mengidentifikasi simpul kunci dalam graf berdasarkan berbagai kriteria, seperti jumlah koneksi, posisi dalam jalur jaringan, atau kedekatan dengan simpul lainnya.

Centrality Graph: Representasi graf yang menunjukkan jaringan dengan metrik centrality tertentu, yang digunakan untuk memvisualisasikan simpul-simpul yang paling signifikan dalam jaringan berdasarkan metrik yang dipilih.

# Jenis-jenis Centrality dalam Graph
## Degree Centrality
Mengukur pentingnya simpul berdasarkan jumlah koneksi langsungnya. Simpul dengan koneksi terbanyak dianggap paling sentral.

## Closeness Centrality
Mengukur seberapa dekat suatu simpul dengan simpul-simpul lain dalam jaringan. Simpul yang dapat mencapai simpul lain dengan jalur terpendek memiliki nilai closeness centrality tinggi.

## Betweenness Centrality
Mengukur seberapa sering suatu simpul menjadi perantara jalur terpendek antara pasangan simpul lainnya. Simpul ini berperan sebagai jembatan atau penghubung.

## Eigenvector Centrality
Menentukan kepentingan simpul berdasarkan koneksi dengan simpul-simpul penting lainnya. Simpul yang terhubung dengan simpul-simpul berpengaruh akan memiliki nilai lebih tinggi.

## Katz Centrality
Merupakan pengembangan dari eigenvector centrality, di mana setiap koneksi diberi bobot tambahan untuk menghitung pengaruh secara lebih luas.

## Harmonic Centrality
Variasi dari closeness centrality yang mempertimbangkan hubungan jarak secara harmonis, bahkan jika beberapa simpul tidak dapat dicapai.