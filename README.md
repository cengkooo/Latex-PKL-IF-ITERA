# Template LaTeX Laporan PKL IF ITERA

Template ini digunakan untuk menyusun laporan Praktek Kerja Lapangan (PKL)
Program Studi Teknik Informatika, Institut Teknologi Sumatera (ITERA).
Template mengikuti struktur dan ketentuan pada dokumen spesifikasi laporan PKL
yang tersedia di [`SPESIFIKASI.md`](SPESIFIKASI.md).

## Persyaratan

Pastikan perangkat yang digunakan memiliki:

- Distribusi LaTeX yang mendukung XeLaTeX, misalnya MiKTeX atau TeX Live.
- Font Times New Roman. Jika font tersebut tidak tersedia, template akan
  menggunakan TeX Gyre Termes sebagai fallback.
- Editor LaTeX. Visual Studio Code dengan ekstensi LaTeX Workshop dapat
  digunakan, tetapi bukan merupakan keharusan.

Template ini **harus dikompilasi menggunakan XeLaTeX**, bukan `pdflatex`,
karena template menggunakan paket `fontspec`.

## Cara menggunakan

1. Salin atau klon repositori ini ke komputer.
2. Buka folder proyek sebagai satu workspace di editor.
3. Isi identitas laporan terlebih dahulu pada
   [`config/metadata.tex`](config/metadata.tex), termasuk:
   - judul laporan dan topik PKL;
   - tahun laporan;
   - nama dan NIM mahasiswa;
   - nama serta kota instansi;
   - data pembimbing dan penanggung jawab instansi;
   - tanggal pengesahan dan nomor pegawai.
4. Ganti teks petunjuk atau contoh pada berkas-berkas di folder
   [`chapter/`](chapter/) dengan isi laporan PKL. Struktur berkas utamanya
   adalah:
   - `cover.tex`: halaman sampul;
   - `pengesahan-prodi.tex` dan `pengesahan-instansi.tex`: lembar pengesahan;
   - `abstrak.tex` dan `kata-pengantar.tex`: bagian awal;
   - `bab1-pendahuluan.tex` sampai `bab6-kesimpulan-saran.tex`: isi utama;
   - `referensi.tex`: daftar pustaka;
   - `lampiran-a.tex` sampai `lampiran-d.tex`: lampiran.
5. Tambahkan atau ganti gambar pada folder [`figure/`](figure/), lalu pastikan
   nama file dan ekstensi pada perintah `\includegraphics` sesuai. Path gambar
   ditulis relatif terhadap [`main.tex`](main.tex), contohnya:

   ```latex
   \includegraphics[width=8cm]{figure/nama-gambar.png}
   ```

6. Perbarui referensi dan sitasi pada
   [`chapter/referensi.tex`](chapter/referensi.tex). Gunakan gaya IEEE,
   minimal 10 referensi, dan maksimal 3 referensi dari website.
7. Kompilasi [`main.tex`](main.tex) menggunakan XeLaTeX. Jalankan kompilasi
   setidaknya dua kali agar daftar isi, nomor halaman, dan daftar gambar/tabel
   diperbarui dengan benar.
8. Periksa PDF hasil kompilasi, terutama halaman sampul, lembar pengesahan,
   daftar isi, sitasi, gambar, nomor halaman, dan lampiran.

## Kompilasi dari terminal

Jalankan perintah berikut dari folder proyek:

```text
xelatex -interaction=nonstopmode -file-line-error main.tex
xelatex -interaction=nonstopmode -file-line-error main.tex
```

Jika perintah `xelatex` tidak ditemukan, tambahkan lokasi instalasi MiKTeX
atau TeX Live ke `PATH`, atau gunakan perintah kompilasi dari ekstensi/editor
LaTeX yang sudah dikonfigurasi.

Pada Visual Studio Code, konfigurasi build tersedia di
[`.vscode/settings.json`](.vscode/settings.json). Pilih recipe `xelatex`
melalui LaTeX Workshop atau jalankan build dari file `main.tex`.

## Struktur direktori

```text
.
├── main.tex              # Titik masuk dokumen dan urutan seluruh bagian
├── config/               # Paket, layout, styling, metadata, dan constraints
├── chapter/              # Sampul, bab laporan, referensi, dan lampiran
├── figure/               # Logo, diagram, dan dokumentasi kegiatan
├── referensi/            # Berkas sumber referensi (opsional)
├── references.bib        # Berkas bibliografi (jika diperlukan)
└── SPESIFIKASI.md        # Ketentuan penulisan dan tata letak
```

## Ketentuan penting

- Ukuran kertas A4 dengan margin atas 3 cm, bawah 3 cm, kanan 3 cm, dan kiri
  3,5 cm.
- Font utama Times New Roman 12 pt dan spasi 1,5.
- Judul pada sampul ditulis dengan huruf kapital, tebal, ukuran 16 pt, dan
  maksimal tiga baris.
- Abstrak maksimal 250 kata dan harus berada dalam satu halaman.
- Rumusan masalah, tujuan, dan kesimpulan harus saling berkaitan.
- Setiap gambar dan tabel harus memiliki caption sesuai format penomoran.
- Lampiran A, B, dan D wajib disertakan. Lampiran C berisi dokumen teknis,
  atau surat pernyataan kerahasiaan apabila dokumen teknis bersifat
  *confidential*.

Ketentuan lengkap untuk isi setiap bab dan lampiran dapat dibaca di
[`SPESIFIKASI.md`](SPESIFIKASI.md).

## Berkas hasil kompilasi

XeLaTeX menghasilkan berkas bantu seperti `.aux`, `.log`, `.out`, `.toc`, dan
`.synctex.gz`. Berkas-berkas tersebut tidak diperlukan untuk dibagikan dan
telah diabaikan oleh `.gitignore`. PDF hasil kompilasi dapat dibuka sebagai
[`main.pdf`](main.pdf) setelah proses build berhasil.

## Pemecahan masalah

- **Font tidak ditemukan:** instal Times New Roman atau biarkan template
  menggunakan font fallback TeX Gyre Termes.
- **Gambar tidak ditemukan:** periksa nama file, ekstensi, dan path relatif
  dari `main.tex`.
- **Daftar isi atau nomor halaman belum benar:** kompilasi ulang XeLaTeX.
- **Perintah `xelatex` tidak ditemukan:** periksa instalasi LaTeX dan variabel
  lingkungan `PATH`.
- **PDF tidak berubah:** pastikan tidak ada error pada output kompilasi dan
  tutup PDF yang sedang dikunci oleh aplikasi pembaca PDF.
