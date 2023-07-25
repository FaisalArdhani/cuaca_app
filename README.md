### Cuaca App Simple

Ini adalah aplikasi cuaca sederhana yang dibangun menggunakan Node.js dan Express.js. Aplikasi ini memungkinkan pengguna untuk mencari cuaca berdasarkan nama kota dan menampilkan informasi cuaca seperti suhu, deskripsi, kelembaban, dan banyak lagi.

### Cara Menggunakan Aplikasi

1. Pastikan Anda telah menginstal Node.js di komputer Anda.

2. Unduh atau klon repository ini ke komputer Anda.

3. Buka terminal dan masuk ke direktori proyek.

4. Instal semua dependensi dengan menjalankan perintah berikut:

```
npm install
```

5. Setelah instalasi selesai, jalankan aplikasi dengan perintah:

```
npm run serve
```

6. Buka browser dan akses aplikasi melalui alamat http://localhost:3000/

7. Ketikkan nama kota yang ingin Anda cari cuaca-nya pada kotak input dan klik tombol "Get Weather".

8. Aplikasi akan menampilkan informasi cuaca berdasarkan kota yang Anda masukkan.

### Struktur Direktori

```
weather_app/
  |- api/
  |  |- node_modules/
  |  |- .env
  |  |- package.json
  |  |- package-lock.json
  |  |- .gitignore
  |  |- server.js
  |- public/
  |  |- css/
  |  |  |- style.css
  |- views/
  |  |- index.ejs
```

### Dependensi Utama

- Express.js: Framework Node.js yang digunakan untuk meng-handle routing dan middleware.
- Body-parser: Middleware untuk meng-handle data dari form input.
- Request: Package untuk melakukan HTTP request ke API cuaca.
- Dotenv: Package untuk menyimpan konfigurasi sensitif seperti API key.

### Konfigurasi

Pastikan Anda memiliki file `.env` di dalam direktori `api/` dan mengatur variabel berikut:

```
API_KEY=YOUR_OPENWEATHERMAP_API_KEY
PORT=3000
```

Gantilah `YOUR_OPENWEATHERMAP_API_KEY` dengan kunci API Anda dari OpenWeatherMap.

### Lisensi

[MIT](LICENSE)

Aplikasi ini dilisensikan di bawah lisensi MIT yang mengizinkan Anda untuk menggunakan, mengubah, dan mendistribusikan kode dengan bebas.
