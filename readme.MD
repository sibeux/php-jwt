# Sihalal PHP JWT

## Deskripsi

Proyek ini adalah implementasi JSON Web Token (JWT) menggunakan PHP untuk aplikasi e-commerce **Sihalal**. JWT digunakan untuk mengautentikasi pengguna dan mengamankan endpoint dalam aplikasi.

## Fitur

- Autentikasi pengguna menggunakan JWT
- Endpoint login untuk menghasilkan token
- Keamanan data dengan menggunakan algoritma enkripsi

## Endpoint

- **Login**: [https://sibeux.my.id/project/sihalal-php-jwt/login](https://sibeux.my.id/project/sihalal-php-jwt/login)

### Metode

- **POST**: `/login`
  - **Parameter**:
    - `username`: Nama pengguna
    - `password`: Kata sandi pengguna

### Contoh Permintaan

```bash
curl -X POST https://sibeux.my.id/project/sihalal-php-jwt/login \
-H "Content-Type: application/json" \
-d '{
  "username": "your_username",
  "password": "your_password"
}'
```

### Contoh Respons

```json
{
  "token": "your_jwt_token"
}
```

## Instalasi

1. Clone repositori ini:

   ```bash
   git clone https://github.com/sibeux/sihalal-php-jwt.git
   ```

2. Masuk ke direktori proyek:

   ```bash
   cd sihalal-php-jwt
   ```

3. Instal dependensi yang diperlukan (jika ada).

4. Sesuaikan pengaturan di file konfigurasi (misalnya, database).

## Cara Menggunakan

1. Jalankan server PHP lokal atau unggah ke server.
2. Akses endpoint yang tersedia untuk melakukan login.
3. Gunakan token yang diterima untuk mengakses endpoint yang memerlukan autentikasi.

## Penulis

- **M. Nasrul Wahabi** - [Profil GitHub](https://github.com/sibeux)

## Kontak

Jika ada pertanyaan, silakan hubungi saya melalui email di [wahabinasrul@gmail.com](mailto:<wahabinasrul@gmail.com>).
