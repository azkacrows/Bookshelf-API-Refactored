# Bookshelf API Refactored oleh Dicoding

## Deskripsi Proyek

Proyek ini merupakan hasil refaktor dari aplikasi Bookshelf API yang saya buat sebelumnya dengan tujuan sebagai bagian dari submission kursus "Belajar Membuat Aplikasi Back-End untuk Pemula" oleh Dicoding. Tujuan dari refaktor ini adalah untuk memperbaiki struktur kode dan meningkatkan kualitas aplikasi agar lebih mudah dikelola dan di-scale. Aplikasi ini dirancang untuk menyimpan, mengelola, dan mengakses data buku melalui API yang dikembangkan menggunakan Node.js dan Hapi.js.

## Struktur Proyek

-   `src/`
    -   `book.js`
    -   `handler.js`
    -   `routes.js`
    -   `server.js`

### Penjelasan Folder dan File

#### `src/`

Folder `src` berisi semua file source code utama dari aplikasi Bookshelf API.

-   `book.js`: Berisi model atau struktur data buku yang digunakan dalam aplikasi.
-   `handler.js`: Berisi fungsi-fungsi handler yang digunakan untuk menangani berbagai request HTTP yang masuk ke server.
-   `routes.js`: Berisi definisi rute API yang menghubungkan endpoint dengan handler yang sesuai.
-   `server.js`: Berisi konfigurasi dan inisialisasi server Hapi.js, termasuk pengaturan plugin dan middleware.

## Fitur Utama

1. **CRUD Buku**: API untuk membuat, membaca, memperbarui, dan menghapus data buku.
2. **Validasi Input**: Validasi data input untuk memastikan integritas data yang disimpan.
3. **Struktur Kode yang Bersih**: Refaktor kode untuk meningkatkan keterbacaan dan pemeliharaan aplikasi.
4. **Penggunaan Hapi.js**: Memanfaatkan framework Hapi.js untuk membangun server yang modular dan fleksibel.

## Cara Menggunakan

1. **Clone Repository**:

    ```sh
    git clone https://github.com/azkacrows/bookshelf-api-refactored.git
    ```

2. **Install Dependencies**:

    Pindah ke direktori proyek dan install dependencies yang diperlukan dengan perintah berikut:

    ```sh
    cd bookshelf-api-refactored
    npm install
    ```

3. **Jalankan Server**:

    Jalankan server dengan perintah berikut:

    ```sh
    npm start
    ```

4. **Gunakan API**:

    Gunakan aplikasi seperti Postman atau curl untuk mengakses endpoint API yang tersedia.

## Sumber Asli

-   **Original Repository**:\
    [Latihan-Bootcamp Bookshelf API](https://github.com/azkacrows/Latihan-Bootcamp/tree/main/Dicoding/submission/Bookshelf-API)
-   **Refactored dari**:\
    [Bookshelf API](https://github.com/azkacrows/bookshelf-API)

**Date**: Jun 11, 2023
