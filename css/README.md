
# Praktikum Desain Web - Form Pendaftaran Kursus

## Identitas Mahasiswa

| Keterangan | Data |
|---|---|
| Nama | Harisa Malfa Liya |
| NPM | 4525210027 |
| Mata Kuliah | Praktikum Desain Web |
| Tugas | Form Pendaftaran Kursus Mahasiswa |

---

## 1. Deskripsi Tugas

Pada praktikum ini, mahasiswa diminta membuat sebuah prototype form pendaftaran kursus untuk mahasiswa baru. Form dibuat menggunakan HTML dan CSS dengan memperhatikan penggunaan elemen input, label, serta tombol yang sesuai.
Form ini dirancang agar nantinya dapat dikembangkan dan diintegrasikan dengan backend untuk pengolahan data pendaftaran.

## 2. Tujuan Praktikum

- Memahami penggunaan elemen form pada HTML.
- Mengenal berbagai tipe input sesuai kebutuhan data.
- Menghubungkan label dengan kontrol menggunakan atribut `for` dan `id`.
- Memahami penggunaan atribut `name` pada setiap field.
- Membuat tampilan form yang rapi dan mudah digunakan.
- Menerapkan CSS agar tampilan responsif pada desktop dan mobile.

## 3. Teknologi yang Digunakan

- **HTML5**: Membuat struktur dan elemen formulir.
- **CSS3**: Mengatur tampilan, warna, ukuran, tata letak, dan responsivitas halaman.
- **Visual Studio Code**: Editor untuk menulis dan mengelola kode program.
- **Google Chrome**: Browser untuk menjalankan dan menguji halaman web.

## 4. Fitur Form

Form pendaftaran memiliki beberapa komponen, yaitu:

| Komponen | Tipe |
|---|---|
| Nama Lengkap | text |
| Email | email |
| Password | password |
| Nilai Akademik | number |
| Tanggal Lahir | date |
| Pilihan Kursus | select |
| Jenis Kelamin | radio |
| Alasan Mengikuti Kursus | textarea |

### Jenis Tombol

1. **Daftar (Submit)**: Mengirim data formulir.
2. **Reset**: Mengosongkan kembali seluruh isian formulir.
3. **Informasi (Button)**: Menampilkan pesan informasi kepada pengguna.

Setiap field telah dilengkapi dengan label serta atribut `id` dan `name` sesuai kebutuhan.

## 5. Struktur Folder Project

```text
PrakDw-Pert07/
│
├── css/
│   └── style.css
│
├── ss/
│   ├── desktop.png
│   └── mobile.png
│
├── index.html
└── README.md
```

## 6. Hasil Running Program

### A. Tampilan Desktop

Berikut merupakan hasil tampilan form pendaftaran kursus ketika dijalankan pada browser desktop.

![ss/desktop.jpg.png](ss/desktop.png)

### B. Tampilan Mobile

Berikut merupakan hasil tampilan form ketika dibuka menggunakan ukuran layar mobile.

![ss/mobile.jpg.png](ss/mobile.png)

## 7. Ringkasan Perubahan, Masalah, dan Solusi

Pada praktikum ini, saya membuat prototype form pendaftaran kursus mahasiswa baru menggunakan HTML dan CSS. Form dilengkapi dengan beberapa tipe input, seperti text, email, password, number, date, select, radio, dan textarea. Selain itu, terdapat tiga jenis tombol, yaitu submit, reset, dan button.

Dalam proses pengerjaan, saya sempat mengalami kendala pada tampilan halaman yang masih polos seperti HTML biasa. Setelah diperiksa, ternyata file CSS berada di dalam folder `css`, sedangkan file HTML berada di folder utama. Masalah tersebut diselesaikan dengan memperbaiki alamat stylesheet menjadi `css/style.css`.

Saya juga menambahkan CSS untuk mengatur warna, jarak, ukuran elemen, serta menggunakan media query agar tampilan dapat menyesuaikan ukuran layar mobile. Hasil akhirnya adalah form pendaftaran yang lebih rapi, mudah digunakan, dan responsif.

## 8. Kesimpulan

Melalui praktikum ini, saya memahami cara membuat formulir menggunakan HTML serta mengatur tampilannya dengan CSS. Penggunaan label, id, name, dan tipe input yang sesuai membantu membuat form lebih terstruktur. Selain itu, penerapan responsive design membuat halaman dapat ditampilkan dengan baik pada desktop maupun perangkat mobile.

---

**Nama:** Harisa Malfa Liya  
**NPM:** 4525210027
