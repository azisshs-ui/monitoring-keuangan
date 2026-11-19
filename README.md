# Monitoring Keuangan Keluarga

Aplikasi PWA untuk mencatat pemasukan, pengeluaran, banyak saldo/rekening, dan rekap bulanan. Dibuat dari workbook Monitoring Keuangan Multi-Saldo Bulanan.xlsx.

## Fitur
- Dashboard saldo, pemasukan, dan pengeluaran.
- Multi-saldo dengan saldo awal per rekening.
- Tambah, ubah, dan hapus transaksi serta kategori.
- Rekap bulanan dan tahunan.
- Ekspor CSV dan backup/restore data JSON.
- Bisa dipasang dari Chrome Android dan tetap dapat digunakan offline setelah dimuat.

## Deploy
Repository ini menyertakan workflow GitHub Actions. Pada Settings → Pages, pilih **Source: GitHub Actions**. Setelah workflow berhasil, situs akan tersedia di halaman GitHub Pages repository ini.

## Pasang di Android
Buka URL GitHub Pages dengan Chrome Android → menu ⋮ → Install app / Tambahkan ke layar utama.

## Data dan privasi
Data transaksi disimpan secara lokal di browser pada perangkat. Tidak ada sinkronisasi otomatis ke perangkat lain. Gunakan menu backup JSON secara berkala.

## Catatan
Ini adalah Progressive Web App (PWA), bukan APK native.