SITEBOOK PWA – PETUNJUK SINGKAT

Isi folder:
- index.html: aplikasi SiteBook
- manifest.json: identitas aplikasi PWA
- service-worker.js: cache dasar untuk dukungan offline
- icons/: ikon aplikasi

CARA MENJALANKAN:
1. Upload SELURUH isi folder ini ke hosting HTTPS (misalnya GitHub Pages atau Netlify).
2. Pastikan index.html berada di folder utama website.
3. Buka URL HTTPS di Android Chrome atau iPhone Safari.
4. Android: menu Chrome > Install app / Add to Home screen.
5. iPhone: Safari > Share > Add to Home Screen.

CATATAN FITUR:
- Data proyek disimpan di localStorage browser/perangkat. Data tidak otomatis tersinkron antar HP.
- Fitur foto progres dan sinkronisasi multi-pengguna masih memerlukan backend; integrasi internal Claude pada file asal tidak tersedia di hosting biasa.
- PDF/Excel sudah disesuaikan agar mengunduh melalui browser. Library PDF/Excel dan font eksternal memerlukan koneksi internet saat pertama kali dimuat.
- Gunakan HTTPS; membuka file HTML langsung (file://) tidak mengaktifkan instalasi PWA.
