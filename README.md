![alt text](image/coverbpf.png?raw=true)

## BAB I Pendahuluan


## 1.1 Tujuan

Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun “Sistem Informasi Ayam Geprek Qiana”. Dokumen ini dibangun untuk memudahkan pengelola Ayam Geprek Qiana dalam memberikan informasi, promosi, dan layanan kepada pelanggan. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak “SISTEM INFORMASI AYAM GEPREK QIANA”.


## 1.2 Lingkup
Sistem Informasi Ayam Geprek Qiana merupakan website yang kami bangun untuk mempermudah pengelola Ayam Geprek Qiana dalam memberikan informasi kepada pelanggan seputar menu makanan, promosi, lokasi restoran, layanan pesan antar, dan berbagai informasi terkait lainnya.

## 1.3 Akronim, singkatan, definisi
| Istilah | Definisi |
| ------ | ------ |
|   SRS     |    Software Requirement Specification    |
|    Login    | Digunakan untuk mengakses aplikasi       |
|   Software Requirement Specification     | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna       |
|    Use Case    | situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda       |

## 1.4 Referensi
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :

- https://fore.coffee/
- https://chatime.co.id/
- https://www.makobakery.com/product



## 1.5 Overview
Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada website. Menjelaskan gambaran umum dari website, 


## BAB II GAMBARAN UMUM  
**Ayam Geprek Qiana** adalah bisnis kuliner yang menawarkan berbagai varian menu ayam geprek dengan cita rasa khas dan pilihan tingkat kepedasan sesuai selera pelanggan. Pada era globalisasi ini, perkembangan teknologi dapat dimanfaatkan untuk meningkatkan promosi dan memberikan informasi yang mudah diakses oleh pelanggan. Dalam proyek ini, kami merancang sebuah **Sistem Informasi Ayam Geprek Qiana** sebagai platform informasi yang berfungsi untuk mendukung pengelola dalam menyampaikan informasi mengenai bisnis Ayam Geprek Qiana secara efektif.  

Sistem informasi ini dirancang untuk memberikan kemudahan kepada pelanggan dalam mengakses informasi seperti menu, lokasi, dan promosi. Selain itu, sistem ini juga membantu pengelola dalam mengelola informasi bisnis mereka dengan lebih terstruktur dan efisien. Berikut adalah fungsi utama yang dirancang untuk sistem informasi ini:  

### **Fungsi untuk Pengunjung/Pelanggan:**
- Melihat menu Ayam Geprek Qiana beserta harga.
- Melihat informasi tentang promosi atau diskon.
- Melihat lokasi dan jam operasional Ayam Geprek Qiana.
- Melihat testimoni pelanggan Ayam Geprek Qiana.
- Mengakses informasi kontak untuk pemesanan atau pertanyaan.

### **Fungsi untuk Admin/Pengelola:**
- Input data menu baru.
- Mengelola promosi atau diskon.
- Mengelola informasi lokasi dan kontak.
- Update, edit, atau hapus data yang sudah ada.

## 2.1 Perspektif produk
Sistem Ayam Geprek Qiana adalah sebuah sistem informasi berbasis website. Terdapat 2 jenis aktor yaitu admin dan pengunjung. Pengolahan data dilakukan oleh admin pada website dan pengunjung hanya melihat informasi pada website.

**2.1.1 Antarmuka Sistem**
![alt text](image/antarmukasistem.png?raw=true)

Sistem Informasi Parenting memiliki 2 pengunjung yaitu admin dan pengunjung. Admin mempunyai fungsi mengelola data informasi dan Pengunjung bisa melihat informasi serta memberikan komentar.

**2.1.2 Antarmuka Pengguna**

**Halaman Admin**
|  |  |
|--|--|
| ![alt text](image/login.png?raw=true) Halaman login admin diminta untuk mengisi username dan password.| ![alt text](image/dashboard.png?raw=true) Setelah login admin akan masuk ke tampilan Dashboard admin.
|  |  |
| ![alt text](image/testimoniadmin.png?raw=true) Pada halaman testimoni, selain menambahkan dan mengedit, admin juga dapat menghapus data testimoni yang mana ketika button hapus di klik akan muncul pop up untuk memastikan admin benar-benar ingin menghapus atau tidak.| ![alt text](image/aboutus.png?raw=true) Pada halaman about us, admin juga dapat mengedit data about us, begitu juga dengan pengelolaan data di kolom tersedia.
|  |  |
| ![alt text](image/menuadmin.png?raw=true) Pada halaman menu, selain menambahkan dan mengedit, admin juga dapat menghapus data menu sesuai dengan kebutuhan admin| ![alt text](image/contactus.png?raw=true) Pada halaman contact us, admin juga dapat mengedit data about us, begitu juga dengan pengelolaan data di kolom tersedia.
|  |  |
| ![alt text](image/registeradmin.png?raw=true) Pada halaman register, admin dapat menambahkan akun untuk mengelola sistem Ayam Geprek Qiana dimana register akan meminta menginputkan nama, email, password, dan konfirmasi password. | ![alt text](image/promoadmin.png?raw=true) Pada halaman promo, admin dapat menambahkan promo, admin dapat menambahkan promo yang tersedia. Terdapat rentang waktu yang dapat diinputkan oleh admin, agar pada tampilan user dapat menegtahui jangka waktu promo yang sedang berlangsung, admin juga dapat menambahkan, mengedit, dan menghapus promo.
|  |  |

**Halaman User**
|  |  |
|--|--|
| ![alt text](image/dashboardUser.png) Pada halaman pengunjung terdapat beranda yang berisi tampilan scrolling yang berisi seluruh konten seperti tampilan home, menu, testimoni, about us, contact us, dan promo.| ![alt text](image/menuuser.png?raw=true) Pada halaman pengunjung terdapat halaman menu, pengunjung dapat melihat informasi seperti variasi menu yang tersedia, harga. Pengunjung juga bisa melakukan pencarian menu pada halaman tersebut.
|  |  |
| ![alt text](image/testimoniuser.png?raw=true) Pada halaman pengunjung terdapat halaman testimoni, pengunjung dapat melihat testimoni pelanggan sebelumnya yang diinputkan oleh admin, seperti informasi mengenai nama, gambar, dan testimoni pelanggan. |![alt text](image/aboutususer.png?raw=true) Pada halaman pengunjung terdapat halaman about us yang berisi judul, gambar, informasi outlet, dan visi misi dari outlet. 
|  |  |
| ![alt text](image/promouser.png?raw=true) Pada halaman pengunjung terdapat halaman promo, pengunjung dapat melihat informasi promo yang ada rentang waktu yang diberikan, juga memberikan informasi promo dan potongan yang berlaku. | ![alt text](image/contactususer.png?raw=true) Pada halaman pengunjung terdapat halaman contact us, pengunjung dapat melihat informasi outlet dengan bantuan maps yang harapannya memberikan kemudahan bagi pelanggan yang baru akan mencoba.
|  |  |


## 2.2 Spesifikasi kebutuhan fungsional
![alt text](image/2.2_UseCase.drawio.png?raw=true)
**2.2.1 Admin Login**

Use Case: Login

Diagram:
![alt text](image/adminLogin.png?raw=true)

Deskripsi Singkat:  
Admin melakukan login terlebih dahulu sebelum masuk ke tampilan dashboard admin. Jika login gagal, akan muncul pesan alert "error login".

Deskripsi Langkah-Langkah: 
1. Admin melakukan login dengan username dan password pada form login.
2. Sistem melakukan validasi login.
3. Jika valid, admin akan diarahkan ke dashboard utama (home admin).
4. Jika tidak valid, sistem akan menampilkan pesan peringatan "error login".

Xref: Bagian 3.2.1, Login Admin

**2.2.2 Admin Register**

Use Case: Register

Diagram:

![alt text](image/adminRegister.drawio.png?raw=true)

Deskripsi Singkat: 
Terdapat form registrasi untuk menambahkan admin baru, yang hanya dapat diakses oleh admin.

Deskripsi Langkah-langkah:
1. Admin dapat mengakses form untuk menambahkan admin baru.
2. Admin mengisi data pada form registrasi.
3. Sistem akan menyimpan data ke database.

Xref: Bagian 3.2.2, Register Admin

**2.2.3 Admin Input Tampilan Dashboard**

Use Case: Input Tampilan Dashboard

Diagram:

![alt text](image/2.2.3.png?raw=true)

Deskripsi Singkat: 
Admin dapat menginputkan tampilan dashboard setelah berhasil login. Dan terdapat gambar dan ucapan singkat saat memasuki dashboard.

Deskripsi Langkah-langkah:
1. Sistem menampilkan tampilan dashboard.
2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload image dan informasi atau ucapan singkat.
3. Sistem akan menyimpan ke database.
4. sudah disimpan sistem akan menampilkan pemberitahuan.

Xref: Bagian 3.2.3, Input Tampilan Dashboard

**2.2.4 Admin Input Data Menu**

Use Case: Input Data Menu

Diagram:
![alt text](image/Menu.png?raw=true)

Deskripsi Singkat: 
Sistem dapat menampilkan halaman input data tentang menu dan Admin dapat menginput data tentang menu-menu yang ada pada Ayam Geprek Qiana.

Deskripsi Langkah-langkah:
1. Sistem akan menampilkan tampilan Menu yang ada pada ayam geprek qiana.
2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload image dan informasi yang terdapat di menu.
3. Sistem akan menyimpan ke database.
4. sudah disimpan sistem akan menampilkan pemberitahuan.

Xref: Bagian 3.2.4, Input Data Menu

**2.2.5 Admin Input Data About Us**

Use Case: Input Data About Us

Diagram:![alt text](image/2.2.5.png?raw=true)


Deskripsi Singkat: 
Sistem dapat menampilkan halaman input About Us tentang Ayam Geprek Qiana dan Admin dapat menginput data tentang Ayam Geprek Qiana.

Deskripsi Langkah-langkah:
1. Sistem akan menampilkan tampilan data tentang About Us.
2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload image dan deskripsi tentang ayam geprek qiana.
3. Sistem akan menyimpan ke database.
4. sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.5, Data About us Ayam Geprek Qiana

**2.2.6 Admin Input Data Promo**

Use Case: Input Data Promo

Diagram:![alt text](image/2.2.6.png?raw=true)


Deskripsi Singkat: 
Sistem dapat menampilkan halaman Input data promo dan Admin mengInput data promo ayam geprek qiana.

Deskripsi Langkah-langkah:
1. Sistem akan menampilkan tampilan data promo ayam geprek qiana.
2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload image, deskripsi, diskon, serta tanggal berlaku dan berakhirnya promo ayam geprek qiana.
3. Sistem akan menyimpan ke database.
4. sudah disimpan sistem akan menampilkan pemberitahuan.

Xref: Bagian 3.2.6, Data Promo

**2.2.7 Contact Us**

Use Case: Data Contact Us

Diagram:![alt text](image/contactUs.png?raw=true)


Deskripsi Singkat: 
Sistem dapat menampilkan data contact us seperti maps dan contact yang dapat dihubungi di halaman user.

Deskripsi Langkah-langkah:
1. Sistem akan menampilkan tampilan data contact us.
2. Admin dapat melihat maps dan kontak yang dapat dihubungi dari ayam geprek qiana.


Xref: Bagian 3.2.7, Data Contact Us

**2.2.8 Admin Input Data Testimoni**

Use Case: Input Data Testimoni

Diagram:![alt text](image/testimoni.png?raw=true)


Deskripsi Singkat: 
Sistem dapat menampilkan halaman input data testimoni dan Admin mengInput data testimoni.

Deskripsi Langkah-langkah:
1. Sistem akan menampilkan tampilan data testimmoni.
2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload gambar dan deskripsi ayam geprek qiana.
3. Sistem akan menyimpan ke database.
4. sudah disimpan sistem akan menampilkan pemberitahuan.

Xref: Bagian 3.2.8, Data Testimoni

**2.2.9 Customer Mengunjungi website**

Use Case: Mengunjungi website

Diagram:
![alt text](image/2.2.9.png?raw=true)

Deskripsi Singkat: 
Customer mengunjungi website dan langsung masuk ke halaman Dashboard sebagai tampilan utama, kemudian melanjutkan ke berbagai fitur seperti Menu untuk mencari atau melihat daftar menu yang tersedia, About Us untuk mengetahui informasi tentang ayam geprek qiana, dan Contact Us untuk melihat kontak serta peta lokasi, Promo untuk melihat informasi promosi, dan Testimoni untuk melihat/membaca review dari pelanggan/customer ayam geprek qiana.

Deskripsi Langkah-Langkah: 
1. Sistem akan menampilkan halaman homepage.
2. Customer dapat memilih fitur yang tersedia di homepage sesuai keinginan seperti fitur Menu, About Us, Contact Us, Promo, dan Testimoni.
3. Apabila memilih fitur Menu maka customer akan dapat melihat atau mecari daftar menu, harga, dll yang tersedia.
4. Apabila memilih fitur About Us maka customer akan dapat melihat Informasi lebih detail mengenai ayam geprek qiana.
5. Apabila memilih fitur Contact Us maka customer akan dapat melihat lokasi ayam geprek qiana dengan maps dan kontak dari ayam gerek qiana yang bisa dihubungi.  Pada tampilan contact us, pengunjung dapat memberikan pertanyaan tanpa perlunya login ke sistem.
6. Apabila memilih fitur Promo maka customer akan dapat melihat promo yang tersedia.
7. Apabila memilih fitur Testimoni maka customer akan dapat melihat atau membaca review dari customer atau pelanggan setia ayam geprek qiana.
8. Customer dapat mengklik homepage kembali jika ingin keluar pada halaman konten yang telah dilihat.

Xref: Bagian 3.2.9, Customer

## 2.3 Spesifikasi kebutuhan non-fungsional
- tabel kebutuhan non-fungsional

| no | deskripsi |
| ------ | ------ |
|     1   |   Semua interface dan fungsi menggunakan Bahasa Indonesia     |
|     2   |   Perangkat Lunak dapat dipakai di semua platofrm OS ( Super Admin, Admin, Customer )     |

## 2.4 Karakteristik Pengguna
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem dan dihubungkan dengan hak akses atau level autentikasi.

## 2.5 Batasan-batasan
tidak ada

## 2.6 Asumsi-asumsi
tidak ada

## 2.7 Kebutuhan Penyeimbang
tidak ada

## BAB III Requirement Specification


## 3.1 Persyaratan Antarmuka Eksternal
Salah satu cara mengakses website ini yaitu customer membuka website nya terlebih dahulu dan masuk ke tampilan dashboard lalu memilih fitur yang tersedia di navbar sehingga dapat melihat konten yang ada di website tersebut.

## 3.2 Functional Requirement
**3.2.1 Login Admin**

| Nama Fungsi         | Login                                  |
| ------------------- | -------------------------------------- |
| Xref                | Bagian 2.2.1, Admin Login               |
| Trigger             | Admin Membuka Website Sistem Ayam Geprek Qiana |
| Precondition        | Halaman login                          |
| Basic Path          | 1. Admin melakukan login dengan username dan password.
|        |         2. Sistem melakukan validasi login. |
|        | 3. Bila sukses, sistem akan mengarahkan ke home admin.  |
|        | 4. Bila gagal, sistem akan menampilkan peringatan. |
|     Alternative       |                   Tidak Ada                   |
| Post Condition     |                  admin dapat login dan mengakses webiste sistem Ayam Geprek Qiana                   |
|         Exception Push          |                  Username dan password salah                   |


**3.2.2 Register Admin**

| Nama Fungsi         | Register                                |
| ------------------- | -------------------------------------- |
| Xref                | Xref: Bagian 2.2.2, Admin Register               |
| Trigger             | Admin Membuka Website Sistem Ayam Geprek Qiana |
| Precondition        | Halaman Register                         |
| Basic Path          | 1. 1. Admin dapat mengakses form untuk menambahkan admin baru.
|        |         2. Admin mengisi data pada form registrasi. |
|        | 3. Sistem akan menyimpan ke database. |
|     Alternative       |                   Tidak Ada                   |
| Post Condition     |                  Setelah registrasi admin dapat login dan mengakses webiste sistem Ayam Geprek Qiana                   |
|         Exception Push          |                  Tidak ada koneksi                |


**3.2.3 Admin Input Tampilan Dashboard**
| Nama Fungsi | Input Tampilan Dashboard |
| ------ | ------ |
| Xref       | Bagian 2.2.3, Admin Input Tampilan Dashboard      |
| Triger       | Membuka website sistem informasi Ayam Geprek Qiana        |
| Precondition | Menginput data tampilan dashboard |
| Basic Path | 1. Sistem menampilkan tampilan dashboard. |
|            | 2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload image dan informasi singkat. |
|            | 3. Sistem akan menyimpan data ke database. |
| Alternative | Tidak ada |     
| Post Condition | Admin mengelola dashboard
| Exception Push | Tidak ada koneksi |


**3.2.4 Input Data Menu**

| Nama Fungsi        | Input Data Menu                              |
| ------------------- | ---------------------------------- |
| Xref               | Bagian 2.2.4, Admin Input Data Menu                     |
| Trigger            | admin dapat menginputkan data Menu |
| Precondition       | Admin menginputkan Data Daftar Menu yang tersedia di Ayam Geprek Qiana |
| Basic Path         | 1. Sistem akan menampilkan tampilan Menu yang ada pada ayam geprek qiana. |
|                    | 2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload image dan informasi yang terdapat di menu.   |
|                    | 3. Sistem akan menyimpan ke database.   |
|                    | 4. Jika sudah disimpan sistem akan menampilkan pemberitahuan.   |
| Alternative        |  Tidak Ada                                 |
| Post Condition     |  Admin Dapat menginputkan data daftar menu seperti gambar, deskripsi, dan harga.        |
| Exception Push     | Tidak Ada        |

**3.2.5 Input Data About Us**

| Nama Fungsi        | Input About Us Ayam Geprek Qiana                              |
| ------------------- | ---------------------------------- |
| Xref               | Bagian 2.2.5, Admin Input Data About Us                     |
| Trigger            | admin dapat menginputkan data About Us Ayam Geprek Qiana |
| Precondition       | Admin menginputkan data informasi lebih detail tentang Ayam Geprek Qiana ke website |
| Basic Path         | 1. Sistem akan menampilkan tampilan data tentang About Us. |
|                    | 2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload image dan deskripsi tentang ayam geprek qiana.   |
|                    | 3. Sistem akan menyimpan ke database.   |
|                    | 4. Jika sudah disimpan sistem akan menampilkan pemberitahuan.   |
| Alternative        |  Tidak Ada                                 |
| Post Condition     |  Admin Dapat menginputkan data About Us seperti visi & misi, latar belakang, dll.        |
| Exception Push     | Tidak Ada        |

**3.2.6 Input Data Promo**

| Nama Fungsi        | Input Informasi Promo                             |
| ------------------- | ---------------------------------- |
| Xref               | Bagian 2.2.6, Admin Input Data Promo                      |
| Trigger            | admin dapat menginputkan data promo |
| Precondition       | Admin menginputkan data promo ke website |
| Basic Path         | 1. Sistem akan menampilkan tampilan data promo ayam geprek qiana |
|                    | 2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload image, deskripsi, diskon, serta tanggal berlaku dan berakhirnya promo ayam geprek qiana.   |
|                    | 3. Sistem akan menyimpan ke database.   |
|                    | 4. Jika sudah disimpan sistem akan menampilkan pemberitahuan.   |
| Alternative        |  Tidak Ada                                 |
| Post Condition     |  Admin Dapat menginputkan data promo seperti nama promo, deskripsi promo, diskon, tanggal berlaku dan berakhirnya promo.        |
| Exception Push     | Tidak Ada        |

**3.2.7  Data Contact Us**

| Nama Fungsi        |  Informasi contact person dan lokasi                              |
| ------------------- | ---------------------------------- |
| Xref               | Bagian 2.2.7, Admin Input Data Contact Us                     |
| Trigger            | admin dapat melihat data contact us|
| Precondition       | Admin melihat data contact us ke halaman user |
| Basic Path         | 1. Sistem akan menampilkan tampilan data contact us. |
|                    | 2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload maps, dan kontak yang dapat dihubungi dari ayam geprek qiana.   |
| Alternative        |  Tidak Ada                                 |
| Post Condition     |  Admin Dapat menginputkan data contact us seputar website seperti lokasi(maps), dan contact person.        |
| Exception Push     | Tidak Ada        |

**3.2.8 Input Data Testimoni**

| Nama Fungsi        | Input Informasi Testimoni                             |
| ------------------- | ---------------------------------- |
| Xref               | Bagian 2.2.8, Admin Input Data Testimoni                      |
| Trigger            | admin dapat menginputkan data testimoni |
| Precondition       | Admin menginputkan data testimoni ke website |
| Basic Path         | 1. Sistem akan menampilkan tampilan data testimmoni. |
|                    | 2. Admin dapat melihat, menambahkan, mengedit, menghapus dan mengupload gambar dan deskripsi ayam geprek qiana.   |
|                    | 3. Sistem akan menyimpan ke database.   |
|                    | 4. Jika sudah disimpan sistem akan menampilkan pemberitahuan.   |
| Alternative        |  Tidak Ada                                 |
| Post Condition     |  Admin Dapat menginputkan data testimoni seperti gambar dan deskripsi.        |
| Exception Push     | Tidak Ada        |

**3.2.9 Mengunjungi website**

| Nama Fungsi        |    Customer  Mengunjungi website             |
| ------------------- | ---------------------------------- |
| Xref               | Bagian 2.2.9 Customer Mengunjungi website             |
| Trigger            |Customer mengunjungi website dan langsung masuk ke halaman homepage sebagai tampilan utama, kemudian melanjutkan ke berbagai fitur seperti Menu untuk mencari atau melihat daftar menu yang tersedia, About Us untuk mengetahui informasi tentang ayam geprek qiana, dan Contact Us untuk melihat kontak serta peta lokasi, Promo untuk melihat informasi promosi, dan Testimoni untuk melihat/membaca review dari pelanggan/customer ayam geprek qiana |
| Precondition       |Customer Mengunjungi website |
| Basic Path         | 1. Sistem akan menampilkan halaman homepage. |
|                    | 2. Customer dapat memilih fitur yang tersedia di homepage sesuai keinginan seperti fitur Menu, About Us, Contact Us, Promo, dan Testimoni.    |
|                    | 3. Apabila memilih fitur Menu maka customer akan dapat melihat atau mecari daftar menu, harga, dll yang tersedia.    |
|                    | 4. Apabila memilih fitur About Us maka customer akan dapat melihat Informasi lebih detail mengenai ayam geprek qiana.    |
|                    | 5. Apabila memilih fitur Contact Us maka customer akan dapat melihat lokasi ayam geprek qiana dengan maps dan kontak dari ayam gerek qiana yang bisa dihubungi. Pada tampilan contact us, pengunjung dapat memberikan pertanyaan tanpa perlunya login ke sistem.    |
|                    | 6. Apabila memilih fitur Promo maka customer akan dapat melihat promo yang tersedia.    |
|                    | 7. Apabila memilih fitur Testimoni maka customer akan dapat melihat atau membaca review dari customer atau pelanggan setia ayam geprek qiana.    |
|                    | 8. Customer dapat mengklik homepage kembali jika ingin keluar pada halaman konten yang telah dilihat.    |
| Alternative        |   Halaman Konten    |
| Post Condition     |   customer mengunjungi website dan melihat informasi yang ada pada website     |
| Exception Push     |    Jika ada kesalahan server atau gangguan teknis, sistem akan menampilkan pesan kesalahan kepada pengguna. Pengguna dapat mencoba kembali atau menghubungi dukungan teknis.    |

## 3.3 Struktur Detail Kebutuhan Non-Fungsional
![alt text](image/ERD_Ayam_Geprek_Qiana.png?raw=true)
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem ayam geprek qiana terdapat pada struktur Database yang dijelaskan menggunakan ERD.

**Tabel Admin**
|Data Item|Tipe Data|Deskripsi|
|--|--|--|
|Id_Admin|int|Auto-increment dari Id_Admin|
|username|varchar|Berisi username admin untuk mengakses sistem|
|Password|varchar|Berisi password admin untuk mengakses sistem|

**Tabel Menu**
|Data Item|Tipe Data|Deskripsi|
|--|--|--|
|id_menu|int|Auto-increment dari Id_menu|
|gambar|varchar|Berisi gambar didalam menu sistem|
|deskripsi|text|Berisi deskripsi menu sistem|
|judul|varchar|Berisi judul pada menu sistem|
|harga|decimal|Berisi harga pada menu sistem|

**Tabel Promo**
|Data Item|Tipe Data|Deskripsi|
|--|--|--|
|id_promo|int|Auto-increment dari Id_promo|
|gambar|varchar|Berisi gambar promo didalam sistem|
|deskripsi|text|Berisi deskripsi promo yang tersedia di sistem|
|judul|varchar|Berisi judul promo di dalam sistem|
|tanggal_berlaku|date|Berisi tanggal berlaku nya promo di dalam sistem|
|tanggal_berakhir|date|Berisi tanggal berakhir nya promo di dalam sistem|
|diskon|decimal|Berisi diskon promo yang tersedia di dalam sistem|

**Tabel about**
|Data Item|Tipe Data|Deskripsi|
|--|--|--|
|id_about|int|Auto-increment dari id_about|
|gambar|varchar|Berisi gambar didalam about sistem|
|deskripsi|text|Berisi deskripsi about sistem|
|judul|varchar|Berisi judul about di dalam sistem|

**Tabel contact**
|Data Item|Tipe Data|Deskripsi|
|--|--|--|
|id_contact|int|Auto-increment dari id_contact|
|kontak|varchar|Berisi isi contact sistem|

**Tabel testimoni**
|Data Item|Tipe Data|Deskripsi|
|--|--|--|
|id_testimoni|int|Auto-increment dari Id_testimoni|
|gambar|varchar|Berisi gambar didalam team sistem|
|nama|text|Berisi nama team sistem|
|deskripsi|text|Berisi deskripsi testimoni sistem|



## Pembagian tugas Dokumen
BAB 1 ->Ruthiana

BAB 2 
2.1
  
  2.1.1 -> Ruthiana
  
  2.1.2 -> Ruthiana
  
  2.1.3 -> Ruthiana
  
  2.1.4 -> Ruthiana
 
  2.1.5 -> Ruthiana
  
  2.1.6 -> Ruthiana
  
  2.1.7 -> Ruthiana
  
  2.1.8 -> Ruthiana

2.2 semua poin-poin (Musarofah)

BAB 3 
3.1 Musarofah
3.2 Musarofah
  3.2.1 Musarofah
  3.2.2 Musarofah
  3.2.3 Musarofah (setelah 3.2.3 itu risky)
3.3 Risky

## Pembagian Tugas Sistem
1. Ruthiana -> Login dan Register, Homepage, Testimoni
2. Musarofah -> About Us, Promo
3. M. Rizky -> Menu, Contact Us
