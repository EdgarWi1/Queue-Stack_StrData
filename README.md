# Queue-Stack_StrData
Edgar Silvanus Limba H071211026

<h3>Pengertian Stack</h3>

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

Operasi-Operasi Dasar Pada Stack 

Ada beberapa operasi dasar yang bisa dilakukan terhadap struktur data stack. Operasi-operasi tersebut meliputi:

a)	Push untuk menyisipkan elemen ke bagian atas stack.
b)	Pop untuk menghapus elemen atas dari stack.
c)	IsEmpty untuk memeriksa apakah stack kosong.
d)	IsFull untuk memerika apakah stack sudah penuh.
e)	Peek untuk mendapatkan nilai elemen teratas tanpa menghapusnya.
