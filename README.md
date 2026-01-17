# PROJECT-UAS-DISKRIT-SMT-1

1️⃣ Pohon Biner dengan 7 Simpul

Pada bagian pertama, program mengimplementasikan pohon biner sederhana yang terdiri dari 7 simpul (node). Setiap simpul direpresentasikan menggunakan class Node, sedangkan pengelolaan pohon dilakukan oleh class BinaryTree.

🔹 Struktur Pohon

Pohon yang dibangun memiliki struktur sebagai berikut:

        A
       / \
      B   C
     / \ / \
    D  E F  G

🔹 Konsep yang Digunakan

Object Oriented Programming (OOP)
Program dipisahkan ke dalam class agar lebih terstruktur dan mudah dikembangkan.

Traversal Pohon Biner, meliputi:

In-order traversal (kiri – akar – kanan)

Pre-order traversal (akar – kiri – kanan)

Post-order traversal (kiri – kanan – akar)

Visualisasi Pohon
Pohon ditampilkan dalam bentuk teks hierarkis untuk memudahkan pemahaman struktur relasi antar simpul.

🔹 Tujuan

Bagian ini bertujuan untuk menunjukkan cara kerja traversal pohon biner serta hubungan parent–child pada struktur data pohon.

2️⃣ Spanning Tree Checker

Bagian kedua berfokus pada analisis graf tak berarah untuk menentukan apakah suatu graf:

Memiliki lebih dari satu spanning tree

Hanya memiliki satu spanning tree

Tidak memiliki spanning tree sama sekali

🔹 Konsep Dasar

Spanning tree adalah subgraf yang:

Menghubungkan seluruh vertex

Tidak mengandung siklus

Memiliki jumlah edge sebanyak V - 1

Program menggunakan pendekatan:

Adjacency List untuk merepresentasikan graf

Depth First Search (DFS) untuk mengecek keterhubungan graf

Perhitungan jumlah edge untuk mendeteksi keberadaan siklus

🔹 Aturan yang Digunakan

Jika graf tidak terhubung, maka tidak memiliki spanning tree

Jika graf terhubung dan jumlah edge = V − 1, maka graf adalah pohon (tepat 1 spanning tree)

Jika graf terhubung dan jumlah edge > V − 1, maka graf memiliki siklus (lebih dari 1 spanning tree)

🔹 Contoh Kasus

Program menyediakan tiga contoh graf:

Graf dengan siklus

Graf yang merupakan pohon

Graf yang tidak terhubung

Setiap contoh disertai dengan hasil analisis dan alasan yang ditampilkan langsung ke layar.

✅ Kesimpulan

Melalui program ini dapat disimpulkan bahwa:

Pohon biner digunakan untuk merepresentasikan data hierarkis dan dapat ditelusuri dengan berbagai metode traversal.

Graf memiliki lebih dari satu spanning tree jika dan hanya jika graf terhubung dan mengandung siklus.

Graf yang merupakan pohon hanya memiliki satu spanning tree.

Graf tidak terhubung tidak memiliki spanning tree.
