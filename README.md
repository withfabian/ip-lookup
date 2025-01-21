# IP Lookup Tool

IP Lookup Tool adalah sebuah aplikasi berbasis web sederhana yang memungkinkan Anda untuk mencari informasi mengenai IP Address, Domain, atau Link. Alat ini dirancang untuk memberikan informasi seperti lokasi geografis, ISP, dan detail lainnya yang relevan dari suatu IP atau domain.

## Fitur Utama
- Mendukung pencarian menggunakan IP Address, domain, atau URL.
- Menampilkan informasi seperti:
  - IP Address
  - Negara
  - Wilayah
  - Kota
  - ISP
  - Latitude dan Longitude
- Antarmuka responsif dan ramah pengguna.

## Teknologi yang Digunakan
- HTML5
- CSS3
- JavaScript (Vanilla)
- [Axios](https://github.com/axios/axios) untuk permintaan HTTP
- [IPInfo API](https://ipinfo.io/) untuk mendapatkan informasi IP.
- [Google DNS API](https://developers.google.com/speed/public-dns/docs/dns-over-https) untuk resolusi domain.

## Cara Menggunakan

### 1. Persiapan
- Pastikan Anda memiliki akses ke internet karena aplikasi ini memerlukan koneksi untuk mengakses API eksternal.
- Salin semua kode dari file HTML ke dalam file baru bernama `index.html`.

### 2. Menjalankan Aplikasi
- Buka file `index.html` di browser favorit Anda.
- Anda akan melihat antarmuka IP Lookup Tool.

### 3. Menggunakan Alat
1. Masukkan IP Address, domain, atau URL di kotak input.
2. Klik tombol **"Cari"**.
3. Informasi akan ditampilkan di bagian hasil jika pencarian berhasil.

### 4. Menangani Kesalahan
- Jika input tidak valid, aplikasi akan meminta Anda untuk memasukkan data yang sesuai.
- Jika API gagal memberikan data, akan muncul pesan kesalahan.

## Contoh Input yang Didukung
- **IP Address**: `8.8.8.8`
- **Domain**: `google.com`
- **URL**: `https://example.com`

## Dokumentasi Kode

### Struktur Utama
1. **HTML**
   - Membuat struktur tampilan utama, termasuk elemen input, tombol, dan area untuk menampilkan hasil.
2. **CSS**
   - Memberikan desain modern dan responsif untuk pengalaman pengguna yang lebih baik.
3. **JavaScript**
   - Menggunakan Axios untuk mengambil data dari IPInfo API.
   - Melakukan validasi input untuk memastikan format data yang benar.

### Fungsi Utama
- **lookupIP()**
  - Bertanggung jawab untuk mengambil input, memvalidasi, dan mengirim permintaan ke API.
- **resolveDomainToIP()**
  - Mengubah domain atau URL menjadi IP menggunakan Google DNS API.

## Lisensi
Hak Cipta © 2025 Fabian Permadi. Semua hak dilindungi undang-undang.

Proyek ini dibuat untuk tujuan pembelajaran dan dapat dimodifikasi sesuai kebutuhan Anda. Jika Anda menggunakan proyek ini dalam pengembangan lebih lanjut, harap sertakan atribusi ke penulis asli.

---

## Kontribusi
Kontribusi sangat dihargai! Jika Anda memiliki ide atau peningkatan, jangan ragu untuk membuat pull request atau membuka issue.

---

