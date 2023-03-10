Nama: Muhammad Yusril Arjulio Prayitno
NIM: 2209116065

Penjelasan Program
Disini saya membuat program searching untuk mencari sebuah index dari nama yang berada di nested list menggunakan 2 algoritma yaitu algoritma jump search dan algoritma Linear search.

fungsionalitas program
fungsi program ini adalah untuk mencari indeks dari data yang ingin dicari menggunakan 2 algoritma search yaitu algoritma jump search dan algoritma linea search dan disini yang akan dicari adalah indeks nama di sebuah nested list atau list bersarang

Cara kerja Program
Pertama, program ini mendefinisikan sebuah list "nama" yang berisi beberapa nama dan satu list nested yang berisi dua nama. Kemudian, program ini mengimport modul math yang digunakan untuk menghitung akar kuadrat dalam algoritma Jump Search.

Program kemudian mendefinisikan dua fungsi yaitu jump_search() dan linear_search(). Fungsi jump_search() mengimplementasikan algoritma Jump Search, sedangkan fungsi linear_search() mengimplementasikan algoritma Linear Search.

Fungsi jump_search() menerima dua parameter yaitu list arr dan nilai yang dicari x. Pertama, program menghitung panjang dari list arr dan membuat variabel jump dengan menghitung akar kuadrat dari panjang tersebut. Selanjutnya, program membuat dua variabel kiri dan kanan yang menunjukkan indeks pada list arr.

Selama nilai pada indeks kiri tidak lebih besar dari nilai yang dicari x dan kiri masih kurang dari panjang list arr, program akan terus melakukan perulangan. Di setiap pengulangan, program memperbarui nilai kanan dengan mencari minimum antara panjang list - satu dan kiri + jump. Kemudian, program memeriksa apakah nilai pada indeks kiri tidak lebih kecil dari nilai yang dicari dan nilai pada indeks kanan tidak lebih besar dari nilai yang dicari. Jika ya, maka program keluar dari perulangan.

Jika nilai pada indeks kiri lebih besar atau sama dengan panjang list arr atau nilai pada indeks kiri lebih besar dari nilai yang dicari x, maka program mengembalikan nilai -1. Jika tidak, program memperbarui nilai kanan dengan mencari minimum antara panjang list arr dikurangi satu dan nilai kanan sebelumnya. Program kemudian melakukan perulangan dari indeks kiri hingga indeks kanan dan memeriksa apakah nilai pada setiap indeks sama dengan nilai yang dicari x. Jika ya, maka program mengembalikan indeks tersebut. Jika tidak, program mengembalikan nilai -1.

Fungsi tampilanjump digunakan untuk menampilkan hasil pencarian elemen dalam array nama menggunakan algoritma Jump Search. Pada fungsi ini terdapat beberapa pemanggilan fungsi jump_search untuk mencari indeks dari beberapa elemen dalam array nama. Setiap elemen dalam array nama dan elemen dalam nested list pada indeks 3 dicari menggunakan algoritma Jump Search, dan indeks dari elemen tersebut kemudian diprint ke terminal.

Fungsi linear_search(), Fungsi ini melakukan perulangan untuk setiap elemen pada list nama dan mengecek apakah nilai pada indeks tersebut sama dengan nilai yang dicari. Jika iya, maka program mencetak indeks dari nilai tersebut. Fungsi ini juga melakukan perulangan untuk setiap elemen pada list nested dan mengecek apakah nilai pada indeks tersebut sama dengan nilai yang dicari. Jika iya, maka program mencetak indeks dari nilai tersebut beserta posisinya di dalam nested list.

Program kemudian mendefinisikan sebuah fungsi menu() yang digunakan untuk memilih algoritma pencarian yang akan digunakan. Program melakukan perulangan yang terus berjalan hingga pengguna memilih untuk keluar dari program. Selama perulangan, program mencetak pilihan menu dan meminta input dari pengguna. Jika pengguna memilih opsi 1, program memanggil fungsi tampilanjump() yang akan melakukan pencarian menggunakan algoritma Jump Search. Jika pengguna memilih opsi 2, program memanggil fungsi linear_search() yang akan melakukan pencarian menggunakan algoritma Linear Search. Jika pengguna memilih opsi lain, program mencetak pesan "Error"
