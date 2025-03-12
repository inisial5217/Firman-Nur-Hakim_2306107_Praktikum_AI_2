Praktikum_Pencarian_Algoritma  

Deskripsi  

Repositori ini berisi implementasi berbagai algoritma pencarian menggunakan Python. Algoritma ini digunakan untuk menemukan jalur atau solusi dalam suatu ruang pencarian. Dalam proyek ini, kami menerapkan berbagai metode pencarian, baik yang tidak menggunakan informasi tambahan (uninformed search) maupun yang memanfaatkan informasi heuristik (informed search).  

Penjelasan Algoritma  

Uninformed Search (Pencarian Tanpa Informasi)  
1. Depth First Search (DFS) – Menelusuri simpul secara mendalam terlebih dahulu sebelum kembali dan menjelajahi jalur lain.  
2. Breadth First Search (BFS) – Mengeksplorasi simpul secara mendatar, dengan menelusuri semua tetangga sebelum melanjutkan ke tingkat berikutnya.  
3. Uniform Cost Search (UCS) – Menggunakan antrian prioritas untuk memilih jalur dengan biaya terendah terlebih dahulu.  

Informed Search (Pencarian dengan Informasi)  
1. Greedy Best-First Search – Memilih simpul berdasarkan nilai heuristik tanpa memperhitungkan biaya perjalanan sebelumnya.  
2. A Tree Search – Mengombinasikan biaya langkah (g) dan nilai heuristik (h) untuk menemukan jalur optimal dalam struktur pohon.  
3. A Graph Search – Mirip dengan A Tree Search, tetapi menghindari eksplorasi ulang simpul yang sudah dikunjungi.  

Cara Menjalankan di Google Colab  
1. Clone repositori ini ke Google Colab atau komputer lokal.  
2. Jalankan skrip yang diinginkan menggunakan Python.  
3. Jika menggunakan Google Colab, unggah file yang diperlukan terlebih dahulu sebelum menjalankan kode.  
