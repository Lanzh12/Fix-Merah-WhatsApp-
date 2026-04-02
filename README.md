🤖 Fix Merah Bot (Telegram)

Bot Telegram simpel yang bantu kirim laporan ke WhatsApp Support kalau kamu kena error:

«“Login not available now”»

Dibikin sengaja ringan, gak ribet, dan langsung jalan. Fokus cuma satu: kirim request dengan cepat.

---

⚡ Cara Pakai Singkat

1. Buka bot di Telegram
2. Klik Start
3. Kirim:

/fixred 628xxxx

Contoh:

/fixred 628123456789

---

✨ Fitur

- Kirim email otomatis ke WhatsApp Support
- Format pesan sudah disusun biar lebih “natural”
- Tidak pakai sistem ribet (no premium, no limit aneh-aneh)
- Ringan → cocok buat panel / Pterodactyl

---

📦 Yang Harus Disiapkan

Sebelum jalanin bot, pastikan kamu punya:

- Node.js (disarankan versi 18 atau 20)
- Akun Telegram
- Akun Gmail

---

🔧 Install

Jalankan di console:

npm init -y
npm install node-telegram-bot-api nodemailer

---

⚙️ Setting Bot

Buka file "bot.js", lalu isi bagian ini:

const TOKEN = "ISI_TOKEN_KAMU"
const EMAIL = "EMAIL_KAMU@gmail.com"
const PASSWORD = "APP_PASSWORD"

Penjelasan:

- TOKEN → dari BotFather (Telegram)
- EMAIL → Gmail kamu
- PASSWORD → App Password (bukan password biasa)

---

🔑 Cara Ambil Token Bot

1. Buka Telegram
2. Cari BotFather
3. Ketik:

/newbot

4. Ikuti langkahnya
5. Copy token yang dikasih

---

🔐 Cara Bikin App Password Gmail

1. Masuk ke pengaturan akun Google
2. Aktifkan Verifikasi 2 Langkah
3. Masuk ke menu App Password
4. Buat password baru untuk “Mail”
5. Pakai password itu di bot

---

▶️ Jalankan Bot

node bot.js

Kalau berhasil, bakal muncul:

BOT SIMPLE RUNNING 🚀

---

🧠 Cara Kerja Singkat

- User kirim "/fixred"
- Bot ambil nomor
- Bot kirim email ke WhatsApp Support
- Selesai

Gak ada proses ribet, gak ada delay aneh — langsung jalan.

---

⚠️ Hal Penting

- Jangan spam request terus-terusan
- Gunakan nomor format internasional ("628xxx")
- Pastikan email & password benar
- Token harus valid

---

❌ Kalau Error

Bot gak respon

- Cek sudah klik "/start"
- Cek token benar

---

Email gagal

- App Password salah
- Gmail belum aktif 2FA

---

Error 404

- Token salah / sudah tidak valid
  → buat ulang di BotFather

---

🔒 Keamanan

- Jangan share token bot ke siapa pun
- Jangan share App Password
- Anggap itu seperti password utama kamu

---

🧩 Catatan

Bot ini sengaja dibuat simpel dulu biar:

- gampang dipakai
- gampang di-debug
- minim error

Kalau sudah stabil, baru bisa ditambah fitur lain.

---

👑 Dibuat oleh

Lam Jr
