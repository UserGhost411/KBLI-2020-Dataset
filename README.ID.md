# Dataset KBLI 2020

Repositori ini berisi dump lengkap dari dataset KBLI (Klasifikasi Baku Lapangan Usaha Indonesia) 2020. KBLI adalah sistem klasifikasi industri standar Indonesia.

## Format Data

Dataset ini saat ini hanya tersedia dalam format `JSON`.

## Struktur Klasifikasi KBLI

Sistem klasifikasi KBLI 2020 disusun secara hierarkis, biasanya terdiri dari tingkatan berikut:

* **Kategori (Section):** Tingkat klasifikasi tertinggi, diwakili oleh satu karakter alfabet.
* **Golongan Pokok (Division):** Kode dua digit, memberikan kategorisasi luas dari kegiatan ekonomi.
* **Golongan (Group):** Kode tiga digit, menawarkan klasifikasi yang lebih spesifik dalam suatu golongan pokok.
* **Subgolongan (Class):** Kode empat digit, merinci jenis kegiatan ekonomi tertentu dalam suatu golongan.
* **Kelompok (Subclass):** Kode lima digit, mewakili tingkat klasifikasi yang paling rinci.



Kode KBLI disusun menggunakan logika digit di mana setiap tambahan digit memperhalus klasifikasi. Contohnya, `A` adalah Kategori, `01` adalah Golongan Pokok dalam Kategori `A`, `011` adalah Golongan dalam Golongan Pokok `01`, dan seterusnya.

| Tingkat Klasifikasi | Format Kode | Deskripsi | Termasuk |
| :--- | :--- | :--- | :--- |
| Kategori | A | Tingkat tertinggi, sektor ekonomi luas | Tidak |
| Golongan Pokok | XX | Kode dua digit, kategori umum | Ya |
| Golongan | XXX | Kode tiga digit, kategori spesifik | Ya |
| Subgolongan | XXXX | Kode empat digit, aktivitas mendetail | Ya |
| Kelompok | XXXXX | Kode lima digit, klasifikasi paling granular | Ya |

## Berkas

Dataset ini disusun ke dalam berkas-berkas berikut:

| Klasifikasi | Nama Berkas | Total Data |
| :--- | :--- | :--- |
| Lengkap | [kbli_lengkap.json](kbli_lengkap.json) | 2686 |
| Golongan Pokok | [kbli_golpok.json](kbli_golpok.json) | 88 |
| Golongan | [kbli_gol.json](kbli_gol.json) | 244 |
| Subgolongan | [kbli_subgol.json](kbli_subgol.json) | 523 |
| Kelompok | [kbli_kelompok.json](kbli_kelompok.json) | 1831 |

## Penggunaan

Dataset ini disediakan untuk tujuan informasi dan analisis. Anda dapat menggunakannya untuk:

* Memahami struktur industri Indonesia.
* Mengkategorikan bisnis berdasarkan aktivitasnya.
* Melakukan analisis statistik terkait sektor ekonomi.
* Mengembangkan aplikasi yang membutuhkan klasifikasi KBLI.

## Informasi Hukum & Penyangkalan

> **PENTING**: Dataset ini disediakan "apa adanya" tanpa jaminan apa pun, baik tersurat maupun tersirat. Meskipun kami mengupayakan akurasi, kami tidak dapat menjamin kelengkapan atau kebenaran dari seluruh informasi yang terkandung di sini.

**Data ini tersedia secara publik di [oss.go.id](https://oss.go.id).**

**Dengan menggunakan dataset ini, Anda mengakui dan setuju bahwa Anda bertanggung jawab penuh atas interpretasi dan aplikasinya. Kami tidak bertanggung jawab atas kerusakan langsung, tidak langsung, insidental, khusus, atau konsekuensial yang timbul dari penggunaan atau ketidakmampuan untuk menggunakan dataset ini, atau untuk tindakan apa pun yang diambil berdasarkan informasi yang disediakan.**

> Dataset ini hanya untuk tujuan informasi umum dan bukan merupakan saran hukum. Harap berkonsultasi dengan profesional hukum yang berkualifikasi untuk masalah hukum atau interpretasi apa pun terkait KBLI atau klasifikasi bisnis.

> Menggunakan data publik ini untuk tujuan yang sah dan etis, sesuai dengan ketersediaan publiknya, tidak seharusnya menimbulkan konsekuensi hukum.
