**1. Kesinambungan PWD–DPW–DPWL** 

PWD, DPW, dan DPWL dapat dipahami sebagai tahapan pembelajaran dalam pengembangan aplikasi web yang saling berhubungan.
PWD menjadi dasar untuk memahami bagaimana halaman web dan aplikasi web dibuat.
DPW mengembangkan pemahaman tersebut ke pembuatan aplikasi web yang lebih dinamis dan terstruktur.
DPWL melanjutkan pengembangan aplikasi ke konsep yang lebih kompleks, salah satunya penggunaan arsitektur MVC (Model–View–Controller).
Kesinambungannya dapat digambarkan sebagai:
PWD → DPW → DPWL → Aplikasi Web yang lebih terstruktur
Artinya, materi pada tahap sebelumnya menjadi dasar untuk memahami materi pada tahap berikutnya. Semakin berkembang aplikasinya, semakin diperlukan struktur program yang jelas agar kode mudah dikembangkan, diperbaiki, dan dipelihara.


**2. Perbedaan PHP Terstruktur dan MVC**
 
PHP Terstruktur
Pada PHP terstruktur, kode program biasanya ditulis dalam satu atau beberapa file berdasarkan alur proses. HTML, PHP, proses pengolahan data, dan koneksi database dapat berada dalam file yang sama.

MVC
Pada MVC, program dibagi menjadi tiga bagian utama:
Model → mengelola data dan database.
View → menampilkan tampilan kepada pengguna.
Controller → mengatur alur antara Model dan View.


**3. Fungsi Model, View, dan Controller** 

A. Model

Model bertugas mengelola data dan berhubungan dengan database.
Contohnya:
Model Mahasiswa
      ↓
Database
      ↓
Data mahasiswa
Tugas Model antara lain:
mengambil data dari database;
memasukkan data;
mengubah data;
menghapus data;
mengatur proses yang berkaitan dengan data.

B. View

View bertugas menampilkan informasi kepada pengguna.
Contohnya:
halaman login;
tabel data mahasiswa;
halaman dashboard;
form input data.
View berfokus pada tampilan/interface.

C. Controller

Controller menjadi penghubung antara Model dan View.
Controller menerima permintaan pengguna, menentukan proses yang harus dilakukan, kemudian mengirimkan hasilnya ke View.
Secara sederhana:
User → Controller → Model → Controller → View → User


**4. Alur Request–Response MVC**

Contohnya, kita ingin melihat data mahasiswa.
Alurnya adalah:
User → Controller → Model → Database → Model → Controller → View → User

Sederhananya:
User meminta data mahasiswa.
Controller menerima permintaan.
Controller meminta data ke Model.
Model mengambil data dari database.
Data dikembalikan ke Controller.
Controller mengirim data ke View.
View menampilkan data kepada User.
Intinya:
Controller mengatur proses, Model mengambil data, dan View menampilkan data.


**5. Pemetaan Fitur Aplikasi DPW ke Model, Controller, dan View**

Contohnya fitur Data Mahasiswa.

**Model**
Mengambil data mahasiswa dari database

**Controller**
Mengatur proses permintaan data mahasiswa

**View**
Menampilkan data mahasiswa di layar

Alasannya: supaya setiap bagian memiliki tugas masing-masing sehingga program lebih rapi dan mudah dipahami.


 **6. Kesimpulan P1**

Dari pembahasan P1 dapat disimpulkan bahwa MVC merupakan cara untuk membuat aplikasi lebih terstruktur dengan membagi program menjadi tiga bagian, yaitu Model, View, dan Controller. Model mengatur data, Controller mengatur proses, sedangkan View menampilkan data kepada pengguna. Dengan pembagian tersebut, aplikasi menjadi lebih rapi, mudah dipahami, dan mudah dikembangkan.