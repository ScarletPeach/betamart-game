# BETAMART — Shift Malam

Prototype game kasir minimarket Indonesia berbasis browser, tanpa framework dan tanpa backend.

## Cara main
1. Buka `index.html` di browser.
2. Tekan **Mulai Shift Malam**.
3. Klik barang untuk memindai, masukkan uang tunai, dan selesaikan transaksi.
4. Gunakan poster DPO dan tombol **Tanya identitas** sebelum memutuskan **Lapor polisi** atau **Bukan buronan**.
5. Layani 6 pelanggan hingga shift berakhir.

## Deploy Cloudflare Pages dari GitHub
- Upload `index.html` dan `README.md` ke root repository.
- Di Cloudflare: Workers & Pages → Create application → Pages → Connect to Git.
- Pilih repository dan branch `main`.
- Framework preset: None; build command: `exit 0` (atau kosong); build output directory: `.`.
- Klik **Save and Deploy**.

## Catatan
- Semua karakter, kasus polisi, dan alamat adalah fiksi.
- Tidak ada data pemain yang dikirim ke server.
- Ini MVP satu episode, tanpa AI generatif ataupun akun online. Fitur AI dialog dan penyimpanan cloud dapat ditambahkan pada tahap berikutnya.
