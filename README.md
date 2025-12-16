# BRI Link Frontend

Frontend aplikasi BUKU KAS BRILink dengan JWT Authentication.

## Setup

1. Pastikan backend API sudah berjalan di `http://localhost:3000`

2. Buka file `index.html` di browser

3. Login dengan:
   - Username: `enggal1933`
   - Password: `12345`

## Konfigurasi API

Jika backend berjalan di URL berbeda, edit di `index.html`:

```javascript
const API_BASE_URL = 'http://localhost:3000/api';
```

Ubah sesuai URL backend Anda.

## Fitur

- ✅ JWT Authentication dengan auto-refresh
- ✅ Real-time clock
- ✅ Transaction management
- ✅ Account balance management
- ✅ Capital flow tracking
- ✅ Settings management
- ✅ PDF export
- ✅ History & reports

## Security

- Token disimpan di localStorage
- Auto logout jika token expired
- Semua API calls menggunakan JWT Bearer token
- Middleware otomatis menambahkan token ke setiap request
