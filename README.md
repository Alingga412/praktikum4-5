## praktikum4-5

### Tugas Praktikum 4

 * soal 


        Buat program sederhana untuk menambahkan data kedalam sebuah
        list dengan rincian sebagai berikut:
        • Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)
        • Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban
          t (Tidak), maka program akan menampilkan daftar datanya.
        • Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
          uts: 35%, uas: 35%)
        • Buat flowchart dan penjelasan programnya pada README.md.
        • Commit dan push repository ke github.



* Gambar 1

![1.png](/gamabar/1.png)

* Gambar 2

![2.png](/gamabar/2.png)


* Hasil dari Output seperti gambar di bawah ini

![3.png](/gamabar/3.png) 



* code

        x = 0
        names = []
        nim = []
        tugas = []
        uts = []
        uas = []
        total = []

        while True:
            nama = input("Nama    : ")
            names.append(nama)
            Nim = input("Nim     : ")
            nim.append(Nim)
            Tugas = input("Tugas   : ")
            tugas.append(Tugas)
            UTS = input("UTS     : ")
            uts.append(UTS)
            UAS = input("UAS     : ")
            uas.append(UAS)
            Total = (int(Tugas)* .30) + (int(UTS)* .35) + (int(UAS)* .35)
            total.append(Total)
    
            data=''
            while data != 'y' and data != 't':
                data = input("Tambah Data (y/t)? ")
        
            x += 1
            if data == 't':
                break
     











### Pratikum 5 

* soal

        Buat program sederhana yang akan menampilkan daftar nilai
        mahasiswa, dengan ketentuan
        • Program dibuat dengan menggunakan Dictionary
        • Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data,
          Tampilkan Data, Cari Data)
        • Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
          uts: 35%, uas: 35%)
        • Buat flowchart dan penjelasan programnya pada README.md.
        • Commit dan push repository ke github.



* gambar 1

![1.png](/gambar2/1.png)

* gambar 2

![2.png](/gambar2/2.png)

* gambar 3

Maka hasil output seperti di gambar ini

![3.png](/gambar2/3.png)

