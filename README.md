# [WEEK 1]- SIPEMA

## `General Analysis`
Pengaduan masyarakat adalah sebuah laporan dari masyarakat kepada pihak atau instansi yang berwenang akan terjadinya suatu penyimpangan, ancaman dalam kehidupan bermasyarakat di sekitarnya. Contoh dari pengaduan masyarakat adalah berupanya penyimpangan yang dilakukan oleh seorang oknum kepolisian saat melakukan tindakan razia, serta ancaman keselamatan yang dilakukan oleh sekelompok orang di daerah Papua. 
		Pada awalnya, pengaduan dilakukan melalui surat yang dikirimkan kepada pemerintah, dan akan diproses 1 - 2 minggu kemudian. Dengan hal yang demikian, dikembangkan sebuah aplikasi berbasis web dengan nama Sistem Informasi Pengaduan Masyarakat (SIPEMA) yang akan mempermudah masyarakat atau pengguna untuk melakukan pengaduan, dan memudahkan pihak berwenang untuk mengumpulkan data dan memproses data data pengaduan dengan cepat.
Melalui Peraturan Menteri Hukum dan HAM Nomor 57 Tahun 2016 tentang Penanganan laporan pengaduan di lingkungan Kementerian Hukum dan HAM.Melalui UU NO. 39 Tahun 1999 mengenai pelanggaran HAM berupa:

a. Hak untuk hidup
b. Hak atas kebebasan pribadi
c. Hak atas rasa keamanan
d. Hak atas kesejahteraan

Adapun tujuan dibangunnya Sistem Informasi Survei Kepuasan Masyarakat yaitu :

1. Mendorong partisipasi masyarakat sebagai pengguna dalam pengakomodiran pengaduan 
2. Sebagai sarana pelaporan dari masyarakat
3. Memudahkan pemrosesan laporan 
4. Meberikan layanan baik guna untuk menampung semua aduan masyarakat.
tahap registrasi user terlebih dahulu mengisi setiap data yang inginkan. Data data yang diperlukan pada tahap registrasi ini antara lain NIK, Nama, tanggal lahir, alamat, jenis kelamin, nomor telepon, email, password. 
	
	Data tersebut akan dicek oleh server secara otomatis, jika terdapat data yang tidak sesuai maka sistem akan memberikan pesan error kemudian user harus mengisi kembali form yang diminta. Setelah proses registrasi berhasil maka user dapat melakukan login terhadap sistem dan mengaksesnya.

	Pada bagian ini user akan masuk ke sistem dengan memasukkan NIK dan password yang sudah di daftarkan di awal pendaftaran.
Setelah melakukan login maka sistem pertama sekali menampilkan dashboard yang merupakan  halaman pertama dari sebuah website setelah kita berhasil masuk ke website tersebut. Halaman ini biasanya berisi informasi mengenai sebuah website dan juga berisi fitur-fitur dengan fungsi yang berbeda-beda. Fitur-fitur yang terdapat pada dashboard adalah home, login dan register.
Pada bagian ini user menginput pengaduan yang akan diadukan pada sistem pengaduan masyarakat. Untuk melakukan pengaduan tersebut, terlebih dahulu user akan berada pada halaman yang memiliki perintah untuk memasukkan identitas user terlebih dahulu, dimana pertama-tama user akan mengisi NIK terlebih dahulu, setelah itu user akan memasukkan nama lengkap sesuai dengan nama di KTP, kemudian memasukkan nomor telepon aktif dari si user agar bisa di hubungi pihak pengaduan masyarakat jika perlu, lalu user akan mengisi alamatnya sesuai yang tertera di KTP juga, lalu memasukkan email aktif dari si user. 

	Setelah selesai mengisi identitas dari pelapor, user akan diperintah untuk melakukan pengisian apa yang akan diadukan, dimana terlebih dahulu user akan mengisi kategori dari yang akan diadukan, contoh kategorinya adalah kriminal, gangguan, kekurangan, dan lain sebagainya. Setelah user selesai memilih kategori lokasi dan waktu kejadian yang akan dilaporkan, kemudian user akan menjelaskan lebih rinci kejadian tersebut agar pihak sistem pengaduan dapat memahami dan memproses tindakan selanjutnya.

## `Fitur SIPEMA`
1.Fitur Registrasi
Merupakan fitur yang digunakan pertama sekali sebelum dapat mengeksplorasi fitur lain. Fitur ini akan menghubungkan user dengan sistem dan akan memiliki akun. Akun tersebut berisi data data diri user  Adapun data yang perlu diisi seperti: ID User, NIK, Username, Nama pengguna
dan Password 

2.Fitur Login
Merupakan fitur yang digunakan setelah melakukan login dan memiliki akun. login akan menghubungkan user dengan website, sehingga user melakukan pengaduan. Sebelum melakukan login, user akan mengisi Nama, NIK, password. 

3.Fitur Home
Merupakan fitur yang digunakan untuk menampilkan tampilan awal yang dimana ketika user mengunjungi system website tersebut maka tampilan home merupakan tampilan awal.

4. Fitur Aduan 
Fitur ini merupakan fitur pengaduan yang menjadi tempat untuk melakukan pengaduan, di dalam fitur ini akan memiliki kategori pengaduan, diantaranya yakni : lokasi kejadian ,waktu kejadian ,keterangan kejadian.file pendukung (jpg, png, mp3, mp4, pdf).

5.Fitur Status 
Fitur ini merupakan fitur yang  berisi tentang pengelolahan dan status dari pengaduan yang disampaikan oleh user atau pengguna. Pada fitur ini pengguna dapat melihat hasil aduan yang disampaikan.


## `Kebutuhan Functional BPMN`
# LOGIN
![image](https://user-images.githubusercontent.com/70965891/188416612-0742778d-f7cc-4c31-aebb-7c7f80dc6bfd.png)

#BPMN Aduan
![image](https://user-images.githubusercontent.com/70965891/188416715-7ed1eb6f-554d-447c-a2c0-4b57bd666aa4.png)

#BPMN Status
![image](https://user-images.githubusercontent.com/70965891/188416792-e4b39d15-d99b-4c63-9749-d8d032acbdfb.png)


## `ERD, CDM, PDM`
#ERD
![image](https://user-images.githubusercontent.com/70965891/188417022-b194718f-663b-4fbd-b2ed-721f0c4cb3a6.png)
#CDM
![image](https://user-images.githubusercontent.com/70965891/188417081-fb08945f-7517-4421-94f2-e37edfff426e.png)
#PDM
![image](https://user-images.githubusercontent.com/70965891/188417130-6806e2b6-340a-4139-be7c-018bef5aee99.png)


