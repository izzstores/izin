# Database Izin IP Autoscript - IZZ TUNNELING

File `ip` di repositori ini digunakan untuk autentikasi dan pengecekan izin IP VPS autoscript `sctun-v4`.

## Format Penulisan:
```text
### <nama_user> <exp_date> <ip_vps>
```

### Keterangan:
- `<nama_user>`: Nama klien / pemilik VPS (tanpa spasi).
- `<exp_date>`: Tanggal kedaluwarsa format `YYYY-MM-DD` (contoh: `2027-12-31`) atau tulis `Lifetime` untuk akses tanpa batas.
- `<ip_vps>`: Alamat IPv4 publik VPS klien.

### Contoh:
```text
### admin Lifetime 127.0.0.1
### client1 2027-06-30 103.196.153.94
### client2 Lifetime 103.197.190.71
```
