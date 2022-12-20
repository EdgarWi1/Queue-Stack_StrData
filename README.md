# Queue-Stack_StrData
Edgar Silvanus Limba H071211026

<h2>Pengertian Stack</h2>

Stack adalah suatu struktur data yang terbentuk dari barisan hingga yang terurut dari satuan data. Pada Stack, penambahan dan penghapusan elemennya hanya dapat dilakukan pada satu posisi, yaitu posisi akhir stack. Posisi ini disebut Puncak atau Top dari stack. Berkebalikan dengan Queue atau antrian yang mana data yang masuk terlebih dahulu akan diproses terlebih dahulu.

<h3>Jenis-Jenis Stack</h3>

Berdasarkan kemampuan menyimpan data, struktur data stack dapat dibagi menjadi 2 jenis, yaitu: 

a)	Register stack

	Register stack merupakan stack yang hanya mampu menampung data dalam jumlah yang kecil. Kedalaman maksimum pada register stack cenderung dibatasi karena ukuran unit memorinya sangat kecil dibandingkan dengan memory stack. 


b)	Memory stack

	Pada stack jenis ini, kedalaman dari stack cukup fleksibel dan mampu menangani dalam dalam skala yang lebih besar dibandingkan jenis sebelumnya. 


<h3>Karakteristik Stack</h3>

Struktur data stack memiliki ciri sebagai berikut: 

a)	Stack diimplementasikan dengan struktur data array atau linked list. 

b)	Mengikuti prinsip operasi (Last In, First Out), yaitu elemen yang dimasukkan pertama akan muncul terakhir dan sebaliknya. 

c)	Penyisipan dan penghapusan terjadi di satu ujung yaitu dari atas tumpukan. 

d)	Apabila ruang memori yang dialokasikan untuk struktur data stack sudah penuh namun masih dilakukan operasi penyisipan elemen maka akan terjadi stack overflow. 

e)	Apabila struktur data tidak memiliki elemen data atau kosong, namun tetap dilakukan operasi penghapusan maka akan terjadi stack underflow.


<h3>Operasi-Operasi Dasar Pada Stack</h3>

Ada beberapa operasi dasar yang bisa dilakukan terhadap struktur data stack. Operasi-operasi tersebut meliputi:

a)	Push untuk menyisipkan elemen ke bagian atas stack.

b)	Pop untuk menghapus elemen atas dari stack.

c)	IsEmpty untuk memeriksa apakah stack kosong.

d)	IsFull untuk memerika apakah stack sudah penuh.

e)	Peek untuk mendapatkan nilai elemen teratas tanpa menghapusnya.



<h2>Pengertian Queue</h2>

Queue adalah struktur data dimana data yang pertama kali dimasukkan adalah data yang pertama kali bisa dihapus. Atau bisa juga disebut dengan struktur data yang menggunakan mekanisme FIFO (First In, First Out). Berbeda dengan struktur data stack yang menyimpan data secara bertumpuk dimana hanya terdapat satu ujung yang terbuka untuk melakukan operasi data, struktur data queue justru disusun secara horizontal dan terbuka di kedua ujungnya. Ujung pertama (head) digunakan untuk menghapus data sedangkan ujung lainnya (tail) digunakan untuk menyisipkan data.

<h3>Jenis-Jenis Queue</h3>

Secara umum ada 4 jenis struktur data queue, meliputi:

a)	Simple Queue
	Simple queue adalah struktur data queue paling dasar di mana penyisipan item dilakukan di simpul belakang (rear atau tail) dan penghapusan terjadi di simpul depan (front atau head).

b)	Circular Queue

	Pada circular queue, simpul terakhir terhubung ke simpul pertama. Queue jenis ini juga dikenal sebagai ring buffer karena semua ujungnya terhubung ke ujung yang lain. Penyisipan terjadi di akhir antrian dan penghapusan di depan antrian.

c)	Priority Queue

	Priority queue adalah strruktur data queue dimana simpul akan memiliki beberapa prioritas yang telah ditentukan. Simpul dengan prioritas terbesar akan menjadi yang pertama dihapus dari antrian. Sedangkan penyisipan item terjadi sesuai urutan kedatangannya.

d)	Double-Ended Queue (Dequeue)

	Dalam double-ended queue (dequeue), operasi penyisipan dan penghapusan dapat terjadi di ujung depan dan belakang dari queue.



<h3>Karakteristik Queue</h3> 

Queue memiliki berbagai karakteristik sebagai berikut: 

a)	Queue adalah struktur FIFO (First In, First Out).

b)	Untuk menghapus elemen terakhir dari Queue (semua elemen yang dimasukkan sebelum elemen tersebut harus dihilangkan atau dihapus). 

c)	Queue adalah daftar berurutan dari elemen-elemen dengan tipe data yang serupa.


<h3>Operasi-Operasi Dasar Pada Queue</h3>

Queue adalah struktur data abstrak (ADT) yang memungkinkan operasi berikut: 

a)	Enqueue untuk menambahkan elemen ke akhir antrian.

b)	Dequeue untuk menghapus elemen dari depan antrian.

c)	IsEmpty untuk memeriksa apakah antrian kosong.

d)	IsFull untuk memeriksa apakah antrian sudah penuh.

e)	Peek untuk mendapatkan nilai bagian depan antrian tanpa menghapusnya.

f)	Initialize untuk membuat antrian baru tanpa elemen data (kosong).

Namun, secara umum antrian memiliki 2 operasi utama, yaitu enqueue dan dequeue. 


<h3>Operasi Enqueue</h3> 

Di bawah ini adalah langkah-langkah untuk enqueue (memasukkan) data ke dalam antrian:

a)	Periksa apakah antrian sudah penuh atau tidak. 

b)	Jika antrian penuh-cetak kesalahan overflow dan keluar dari program. 

c)	Jika antrian tidak penuh-naikkan pointer belakang untuk menunjuk ke ruang kosong berikutnya. 

d)	Tambahkan elemen pada posisi yang ditunjuk oleh pointer belakang. 

e)	Kembalikan status bahwa penambahan telah berhasil.
