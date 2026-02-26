# Real Estate Customer Service Automation (n8n)

## 🏡 Project Overview
Automation system untuk membantu Customer Service perumahan dalam:

- Auto balas chat masuk
- Klasifikasi tipe lead
- Auto follow up H+1 / H+3
- Reminder booking
- Simpan data ke Google Sheets
- Notifikasi ke tim sales

## 🎯 Tujuan
Meningkatkan respon time CS & menaikkan conversion rate tanpa harus manual follow up.

## ⚙️ Workflow Logic

1. User kirim chat
2. Webhook menerima pesan
3. System cek:
   - Sudah pernah chat?
   - Sudah booking?
4. Kirim auto reply sesuai kategori
5. Schedule follow up otomatis
6. Stop automation jika status = deal

## 🛠 Tools
- n8n
- WhatsApp API
- Google Sheets
- Webhook

## 🔐 Security
Credential & API key tidak disertakan demi keamanan client.
