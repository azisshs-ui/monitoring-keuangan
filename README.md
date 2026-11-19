# Monitoring Keuangan Keluarga

Aplikasi Progressive Web App (PWA) untuk pencatatan keuangan keluarga, dibuat agar nyaman digunakan dari browser HP dan dapat dipasang ke layar utama Android.

## Fitur
- Dashboard total saldo dan ringkasan pemasukan/pengeluaran bulanan.
- Multi-saldo/rekening dengan saldo awal masing-masing.
- Tambah, ubah, dan hapus transaksi.
- Kelola daftar saldo dan kategori.
- Rekap pemasukan/pengeluaran per bulan dan tahun.
- Ekspor transaksi ke CSV.
- Cadangkan dan pulihkan data melalui JSON.
- Penyimpanan lokal di perangkat dan akses offline setelah aplikasi dibuka pertama kali.

## Data awal
- Tabungan: saldo awal Rp10.587.000.
- Kebutuhan: saldo awal Rp4.483.000.
- Pemasukan 1 Oktober 2026: Rp53.044.000 ke Kebutuhan.
- Pengeluaran 31 Oktober 2026: Rp49.961.000 dari Kebutuhan.
- Saldo gabungan awal dan transaksi contoh: Rp18.153.000.

Data awal dapat diubah atau dihapus melalui aplikasi.

## Aktifkan GitHub Pages
1. Buka tab **Settings** pada repository.
2. Pilih **Pages** di menu samping.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch **main** dan folder **/(root)**, lalu tekan **Save**.
5. Tunggu proses publikasi selesai. Alamat situs biasanya berbentuk `https://azisshs-ui.github.io/monitoring-keuangan/`.

## Pasang di Android
1. Buka alamat GitHub Pages tersebut di Google Chrome Android.
2. Ketuk menu **⋮**.
3. Pilih **Install app** atau **Tambahkan ke layar utama**.
4. Ikuti konfirmasi. Ikon aplikasi akan muncul di layar utama.

## Catatan penyimpanan
Data disimpan di browser/perangkat yang digunakan, bukan di server. Data tidak otomatis tersinkronisasi antar-HP. Cadangkan JSON secara rutin melalui menu **Pengaturan** dan simpan di tempat aman. Untuk pindah perangkat, pulihkan file JSON di perangkat baru.

Aplikasi ini adalah PWA, bukan APK native. Pemasangan PWA memerlukan alamat HTTPS.