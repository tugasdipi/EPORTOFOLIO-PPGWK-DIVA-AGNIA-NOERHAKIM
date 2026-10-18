# E-Portofolio Guru Berdampak SDGs — PPGWK 4.F

**Diva Agnia Noerhakim, S.Pd. · NIM 2530709**  
PPG Calon Guru Gelombang 1 Tahun 2026 · IPS · Universitas Pendidikan Indonesia

## Isi website

Website e-portofolio satu halaman (single-page) dengan enam bab:

1. **A — Profil Profesional Berwawasan Keberlanjutan**
2. **B — Refleksi Kontribusi terhadap SDGs**
3. **C — Portofolio Aksi SDGs** (TRIFIN, Local Wisdom Explorer, FinEvo.id) dengan bukti daring
4. **D — Peta Karier Profesional 2027–2031** (interaktif, enam komponen tiap tahun)
5. **E — Rencana Aksi SDGs di Sekolah** (program satu tahun ajaran)
6. **Refleksi akhir** (ketujuh pertanyaan LMS)

Tersedia daftar sumber dan referensi serta tombol **Cetak laporan** untuk menghasilkan versi **6 halaman A4** dari jendela cetak browser (pilih *Save as PDF*). **File PDF 6 halaman siap dibaca juga telah disertakan** dalam paket.

## Pembaruan: perbaikan tata letak Refleksi Akhir

- Struktur dua kolom dikoreksi agar judul, narasi, dan kutipan di kiri tidak tertindih pertanyaan di kanan.
- Tombol *Mode baca nyaman* dan *Salin tautan portofolio* berada di atas daftar tujuh pertanyaan.
- Pada layar tablet dan ponsel, seluruh isi tersusun vertikal dan tidak saling tumpang tindih.
- Perbaikan diuji pada layar 320, 390, 768, 1024, 1440, dan 1875 piksel.
- Jika setelah deploy masih melihat desain lama, tunggu GitHub Pages memperbarui situs lalu muat ulang dengan `Ctrl + Shift + R`.

## Cara deploy ke GitHub Pages

1. Buat repository baru di akun GitHub.
2. Unggah **seluruh isi folder** ini ke akar repository (file `index.html`, `README.md`, dan folder `dokumen/`), **bukan** folder luarnya.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch** kemudian **main** dan **/(root)**, lalu klik **Save**.
5. Setelah situs terbit, tautan mengikuti format `https://<username>.github.io/<nama-repository>/`.

Alternatif: unggah ZIP melalui opsi *Upload files* setelah diekstrak di komputer. GitHub umumnya memerlukan file yang diekstrak, bukan file ZIP tunggal di dalam repository.

## Cara menyimpan laporan PDF

- Buka website menggunakan Chrome / Edge.
- Klik tombol **Cetak laporan**.
- Pilih **Save as PDF**, ukuran kertas **A4**, skala **100% / Default**, margin **None**, header/footer browser **nonaktif**, serta **Background graphics aktif** bila tersedia.
- Hasil yang dituju adalah 6 halaman. Beberapa mesin browser/driver cetak dapat mengubah hasil pemenggalan; periksa sebelum unggah.

## Struktur berkas

```text
index.html
README.md
dokumen/
  Makalah_SDGs_CPD_2026.pdf
Laporan_4F_6_Halaman.pdf
```

Tata letak, animasi ringan, grafik, dan ikon tetap bersifat **inline** (HTML/CSS/JS/SVG). Website tidak memerlukan paket npm atau backend. **Pengecualian: logo TRIFIN dan logo Local Wisdom Explorer di bagian C mengambil aset resmi dari situs/repository asli melalui internet**; keduanya memiliki fallback jika jaringan tidak tersedia. Tautan produk sumber tetap mengarah ke website aslinya.

## Catatan akademik

- Sumber utama: makalah SDGs–CPD tahun 2026, presentasi karya inovasi, website TRIFIN, Local Wisdom Explorer, dan FinEvo.id.
- **TRIFIN:** bukti implementasi dan rubrik observasi tersedia; hasil bukan uji kausal literasi finansial.
- **Local Wisdom Explorer:** bukti penggunaan sebagai asesmen awal dan data rekap 26 murid berasal dari bahan pelaksanaan PPL.
- **FinEvo.id:** produk tersedia; dampak implementasi dan perubahan perilaku konsumsi belum dibuktikan.
- Periode **2027–2031** dan program **Smart Spending, Sustainable Living** merupakan rencana target, bukan klaim pelaksanaan.
- Portofolio digital menguraikan 5 komponen inti, ditambah refleksi dan sumber. Karena format LMS mensyaratkan 4–6 halaman, gunakan fitur cetak 6 halaman apabila penilaian/unggahan memerlukan dokumen halaman tetap.
- Hindari menerbitkan kode akses privat, PIN siswa, data siswa yang mengidentifikasi individu, atau dokumen internal yang belum disetujui untuk publik.

## Peningkatan yang dapat dilakukan

Jika memperoleh dokumentasi tambahan, Anda dapat memperbarui bagian aksi dengan foto dokumentasi yang diizinkan untuk publik, laporan observasi, sertifikat CPD, dan rekap asesmen anonim. Foto profesional tetap tersemat langsung dan tidak menggunakan gambar eksternal. Di bagian C, dua logo sumber diambil secara daring dan memiliki tampilan cadangan untuk koneksi terputus.


## Pembaruan Foto Profil

Dua foto profesional asli pemilik portofolio telah ditambahkan: almamater UPI di hero/beranda dan jas hitam di bagian A (Profil Profesional). Kedua foto telah ditanam langsung sebagai WebP di `index.html`; **tidak perlu mengunggah file gambar secara terpisah** ke GitHub. Gunakan dokumen portofolio sesuai ketentuan privasi pemilik foto.


## Revisi Komposisi Foto (18 Oktober 2026)

- Foto almamater UPI di bagian pembuka diperbesar dan diberi gradasi halus pada bagian bawah, sehingga tidak ada batas gambar berbentuk kotak yang tampak terpotong.
- Foto berjas hitam ditempatkan di panel potret tersendiri dengan latar yang menyatu dan transisi halus ke identitas profesional.
- Tata letak responsif diperiksa di layar desktop, tablet, dan ponsel. Kedua foto tetap tersemat langsung di berkas HTML.


## Pembaruan Visual Kartu Aksi (18 Oktober 2026)

- **TRIFIN:** logo asli dalam bentuk WebP ditampilkan dari direktori `assets/img` resmi situs TRIFIN. Jika internet tidak tersedia, label TRIFIN cadangan tetap tampil.
- **Local Wisdom Explorer:** logo asli telah disematkan sebagai base64 dalam `index.html` website sumber, sehingga portofolio secara otomatis mengambil data gambar asli dari halaman sumber GitHub saat dibuka secara online. Terdapat fallback tipografi ketika halaman tidak bisa diakses.
- **FinEvo.id:** kartu menggunakan identitas *wordmark* FinEvo.id dengan warna biru tua–biru yang mengikuti gaya tipografi dan warna pada bagian Bank Materi website aslinya; tidak ada file logo raster terpisah yang digunakan.
- Ketiga kartu telah disesuaikan responsif tanpa mengubah judul, uraian, atau tautan bukti tugas 4.F.
- Jika seluruh logo harus berfungsi **sepenuhnya offline tanpa koneksi internet**, tambahkan berkas logo asli TRIFIN dan Local Wisdom Explorer ke repository sebagai aset lokal.


## Pembaruan pengalaman interaktif (Oktober 2026)

- **Navigator lima perspektif:** kartu editorial untuk membuka bagian Profil, Refleksi, Aksi, Karier, dan Program.
- **Pencarian cepat:** klik ikon kaca pembesar atau tekan **Ctrl + K** (Windows) / **⌘ + K** (Mac). Cari nama bagian, karya, dan referensi digital.
- **Lensa SDGs:** tab SDG 4 dan 12 menjelaskan status kontribusi dan perbedaan bukti pelaksanaan dengan rencana pengembangan.
- **Bukti aksi:** tiga kartu portofolio dapat difilter. Setiap kartu memiliki bagian **Bedah proses & keterbatasan bukti** yang dapat dibuka.
- **Peta karier:** tab tahun 2027–2031 menampilkan kompetensi, CPD, jejaring, inovasi, kontribusi, target dampak, dan milestone.
- **Timeline program:** enam tahapan selama satu tahun ajaran dapat diklik, dilengkapi luaran dan status sebagai *rencana*.
- **Panduan pengunjung dan mode baca:** tombol cara menjelajah, tautan salin, serta mode baca nyaman (hanya pilihan tampilan disimpan lokal pada perangkat).
- **Responsif + aksesibilitas:** navigasi keyboard, state tab, dan dukungan `prefers-reduced-motion`.
- **Cetak:** tombol cetak tetap menggunakan tata letak laporan A4 enam halaman khusus, terpisah dari pengalaman layar.

Semua animasi dan interaksi dibuat tanpa library JavaScript tambahan; dokumen dapat di-deploy sebagai GitHub Pages statis. Kedua foto disematkan langsung di `index.html`. Logo digital mengikuti perlakuan pada versi sebelumnya: beberapa logo asli diperoleh dari website sumber ketika perangkat tersambung ke internet; fallback tipografi ditampilkan bila sumber tidak dapat dimuat.

### Perhatian akademik
Perubahan skor observasi TRIFIN adalah **skor proses belajar**, bukan nilai tes literasi finansial atau bukti dampak kausal. FinEvo.id merupakan **produk pengembangan** tanpa klaim uji dampak di kelas. Tahapan Smart Spending dan peta karier adalah **rencana**.

## Audit dan Perapian Responsif (18 Oktober 2026)

- Menghilangkan tinggi paksa pada kartu-kartu profil, sehingga tidak muncul panel kosong berlebihan.
- Menyeimbangkan komposisi foto di dalam kartu profil dan merapikan jarak antar-konten.
- Merapikan gaya judul, label, kartu SDGs, dan grafik untuk lebar desktop serta ponsel.
- Memperbaiki navigasi dan halaman pada layar sempit 320px supaya tidak melebar ke samping.
- Ketika filter aksi hanya menghasilkan satu karya, kartu akan ditampilkan terpusat; dua karya tampil dua kolom pada desktop, satu kolom pada ponsel.
- Pencarian, navigasi, pilihan tahun karier, tab SDGs, dan timeline program kembali diuji di empat ukuran layar.
- CSS versi layar dipisahkan dari aturan cetak sehingga layout laporan enam halaman tetap dipertahankan.


- Revisi terbaru: header menggunakan logo UPI dan PPG, judul brand menjadi “E-Portofolio Diva Agnia Noerhakim”, serta tombol cetak laporan dihapus karena laporan tersedia terpisah.
