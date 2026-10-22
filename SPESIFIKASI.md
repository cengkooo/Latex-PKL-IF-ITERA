# Dokumentasi Spesifikasi, Constraints, dan Peraturan Template Laporan PKL
**Institusi:** Program Studi Teknik Informatika, Institut Teknologi Sumatera (ITERA)  
**Mata Kuliah:** IF4004 Praktek Kerja Lapangan  

Dokumen ini merangkum seluruh aturan penulisan (*constraints*), fitur tata letak dokumen, struktur penomoran, serta ketentuan isi untuk setiap bagian (*section*) berdasarkan dokumen `T1-Template Laporan PKL.docx`.

---

## 1. Peraturan Umum & Tata Letak Dokumen (Global Constraints)

Bagian ini mengatur format dasar fisik dan tipografi dokumen secara keseluruhan:

*   **Tipografi (Font) Utama:** Menggunakan huruf **Times New Roman** ukuran **12 pt** untuk seluruh teks isi laporan.
*   **Batas Halaman (Margin):**
    *   **Atas (Top):** $3\text{ cm}$ ($1.18\text{ in}$)
    *   **Bawah (Bottom):** $3\text{ cm}$ ($1.18\text{ in}$)
    *   **Kanan (Right):** $3\text{ cm}$ ($1.18\text{ in}$)
    *   **Kiri (Left):** $3.5\text{ cm}$ ($1.38\text{ in}$) — *lebih lebar untuk kebutuhan penjilidan*.
*   **Sistem Penomoran Halaman (Pagination Rules):**
    *   **Bab Isi (Bab I – Bab VI & Referensi):**
        *   Halaman pertama pada setiap bab baru: Nomor halaman diletakkan di bagian **Bawah Tengah (*Bottom Center*)**.
        *   Halaman lanjutan dalam bab yang sama: Nomor halaman diletakkan di bagian **Kanan Atas (*Top Right*)**.
    *   **Halaman Lampiran:**
        *   Menggunakan format penomoran berawalan huruf lampiran: `<Huruf Lampiran>-<Nomor Urut>` (contoh: `A-1`, `A-2`, `B-1`, dst.).
        *   Posisi nomor halaman mengikuti aturan bab isi: halaman pertama lampiran berada di **Bawah Tengah (*Bottom Center*)**, dan halaman berikutnya berada di **Kanan Atas (*Top Right*)**.
*   **Aturan *Caption* (Keterangan Gambar & Tabel):**
    *   **Format Penomoran:** `<Nomor Bab>.<Urutan Tabel/Gambar pada Bab Tersebut>` (contoh: `Tabel 4.1.`, `Gambar 2.1.`). Khusus pada bagian Lampiran, menggunakan huruf lampiran (contoh: `Gambar D.1.`).
    *   **Posisi *Caption* Tabel:** Wajib diletakkan di **atas** tabel.
    *   **Posisi *Caption* Gambar:** Wajib diletakkan di **bawah** gambar.
*   **Gaya Sitasi (Citation Style):** Menggunakan penomoran siku gaya **IEEE** (contoh: `[1]`) di dalam teks.

---

## 2. Bagian Awal Dokumen (Front Matter)

### 2.1. Halaman Sampul (Cover Page)
*   **Header Dokumen:** Teks statis `"LAPORAN PRAKTEK KERJA LAPANGAN"`.
*   **Judul Laporan (*Constraints* Ketat):**
    *   Ditulis seluruhnya dalam **HURUF KAPITAL (ALL CAPS)**.
    *   Jenis dan ukuran huruf: **Times New Roman, 16 pt**.
    *   Gaya huruf: **Dicetak tebal (*Bold*)**.
    *   **Batas Panjang:** **Tidak boleh melebihi 3 baris**.
*   **Lokasi Instansi:** Format `"DI <Nama Perusahaan>"`.
*   **Teks Tujuan Pengajuan:** `"Diajukan untuk memenuhi persyaratan kelulusan Matakuliah IF4004 Praktek Kerja Lapangan"`.
*   **Identitas Penulis:** Mencantumkan `Nama mahasiswa` dan `NIM`.
*   **Atribut Visual:** Wajib memuat **Logo Resmi ITERA**.
*   **Footer Sampul:** Teks statis `"PROGRAM STUDI TEKNIK INFORMATIKA"`, `"INSTITUT TEKNOLOGI SUMATERA"`, diikuti tahun penyusunan (`2026`).

### 2.2. Lembar Pengesahan (Terdapat 2 Jenis)
Dokumen wajib memiliki dua lembar pengesahan terpisah:
1.  **Lembar Pengesahan Program Studi Teknik Informatika:**
    *   **Isi:** Topik Kerja Praktek, Nama Perusahaan, Nama Mahasiswa, dan NIM.
    *   **Tempat & Tanggal:** Format `"Lampung Selatan, ……"`.
    *   **Otoritas Pengesah:** Pembimbing Praktek Kerja Lapangan Program Studi Teknik Informatika ITERA (lengkap dengan Nama Pembimbing dan NIP).
    *   **Ketentuan Tanda Tangan:** Dapat menggunakan **tanda tangan digital atau tanda tangan basah** sesuai kesepakatan dengan dosen pembimbing.
2.  **Lembar Pengesahan Instansi/Perusahaan:**
    *   **Isi:** Topik Kerja Praktek, Nama Perusahaan, Nama Mahasiswa, dan NIM.
    *   **Tempat & Tanggal:** Format `"<Kota, Tanggal>"` sesuai lokasi instansi.
    *   **Otoritas Pengesah:** Jabatan Penanggung Jawab / Pembimbing Lapangan di tempat kerja (lengkap dengan Nama Terang dan Nomor Induk Pegawai / Nomor Pegawai).
    *   **Ketentuan Tanda Tangan:** Menggunakan **tanda tangan digital, tanda tangan langsung (basah), dan/atau cap basah** mengikuti ketentuan resmi dari instansi terkait.

### 2.3. Abstrak
*   **Bahasa:** Ditulis dalam Bahasa Indonesia yang baik dan benar.
*   **Komponen Wajib dalam Paragraf Abstrak:**
    1.  Ringkasan lingkup kerja praktek (termasuk menyebutkan nama perusahaan).
    2.  Penjelasan singkat mengenai permasalahan di instansi.
    3.  Pelaksanaan kerja praktek (proses pengerjaan dan pencapaian hasil).
    4.  Kesimpulan umum mengenai kerja praktek yang telah dilakukan.
    5.  **Kata Kunci (*Keywords*):** Ditulis di bagian bawah abstrak dengan format `Kata kunci: …`.
*   **Constraints Panjang & Ruang:**
    *   Maksimal **250 kata**.
    *   Wajib muat hanya dalam **1 halaman**.

### 2.4. Kata Pengantar
*   **Isi:** Ungkapan rasa terima kasih penulis kepada seluruh pihak yang terkait dan membantu pelaksanaan PKL.
*   **Constraint Bahasa:** Wajib menggunakan Bahasa Indonesia yang baik dan benar (baku/formal).

### 2.5. Daftar Isi & Daftar Lain-lain
*   **Daftar Isi:** Memuat struktur bab, subbab, hingga lampiran beserta nomor halamannya secara otomatis.
*   **Daftar Lain-lain (Opsional/Kondisional):**
    *   Mencakup: Daftar Tabel, Daftar Gambar, Daftar Algoritma, Daftar Padanan Istilah, Daftar Singkatan, Daftar Istilah, atau Daftar Simbol.
    *   **Constraint Eksistensi (Aturan Minimum):** Jika di dalam seluruh dokumen **hanya terdapat satu gambar atau satu tabel**, maka **tidak perlu** dibuatkan Daftar Gambar atau Daftar Tabel.
    *   **Constraint Tata Letak:** Setiap daftar (misal: Daftar Gambar, Daftar Tabel, Daftar Istilah) **wajib diletakkan pada halaman yang terpisah**.

---

## 3. Bagian Isi Laporan (Main Body Chapters)

### Bab I: Pendahuluan
Berisi pengantar mengenai PKL yang dilaksanakan.
*   **1.1. Latar Belakang:**
    *   *Definisi Konsep:* Laporan PKL diposisikan sebagai laporan penelitian pemecahan masalah (*problem solving*) di bidang Informatika yang terjadi pada instansi PKL.
    *   *Isi Wajib:* Latar belakang pelaksanaan PKL di perusahaan, substansi yang digeluti (dikaitkan dengan tujuan, misi, visi, atau fungsi perusahaan), masalah nyata di instansi, serta solusi berbasis ilmu informatika yang dipelajari selama kuliah.
    *   **Constraint Larangan (Negative Constraint):** **Dilarang** menjelaskan latar belakang pelaksanaan mata kuliah Praktek Kerja Lapangan secara kurikuler/akademis.
*   **1.2. Rumusan Masalah:**
    *   Berisi permasalahan utama yang mendasari pelaksanaan PKL (dapat ditulis dalam bentuk poin-poin).
    *   *Constraint Keterkaitan:* Setiap poin pada Rumusan Masalah **wajib dijawab** nantinya pada **Bab VI Kesimpulan**.
*   **1.3. Tujuan:**
    *   **Constraint Larangan:** Tuliskan tujuan dari penyelesaian permasalahan teknisnya, **bukan** tujuan mata kuliah PKL seperti yang tertulis di buku kurikulum.
    *   *Constraint Keterkaitan:* Harus selaras lurus dengan Rumusan Masalah dan berkaitan langsung dengan Kesimpulan.
*   **1.4. Manfaat:**
    *   Wajib mencakup manfaat pelaksanaan dan penyelesaian masalah bagi **3 pihak**:
        1.  Secara pribadi (mahasiswa),
        2.  Program Studi Teknik Informatika, dan
        3.  Instansi tempat bekerja.
*   **1.5. Ruang Lingkup:**
    *   Berisi batasan permasalahan dan penyelesaian yang dikerjakan.
    *   *Constraint Kerja Tim:* Jika mahasiswa bekerja di dalam sebuah tim, maka **wajib menuliskan ruang lingkup/porsi kerja praktek spesifik mahasiswa tersebut** sebagai bagian dari tim.
*   **1.6. Sistematika Penulisan:**
    *   Menjelaskan substansi dan cakupan dari draf laporan mulai dari **Bab I sampai dengan Bab VI** yang disesuaikan langsung dengan topik penelitian/PKL yang diangkat.

### Bab II: Gambaran Umum Instansi
Menjelaskan struktur organisasi dan lingkungan kerja tempat praktik berlangsung.
*   **2.1. Profil Organisasi:**
    *   Berisi deskripsi umum perusahaan, sejarah, *key people* (tokoh kunci), dll.
    *   **Constraint Visual Wajib:** **Harus terdapat gambar Logo Perusahaan** beserta *caption*-nya.
*   **2.2. Visi dan Misi Organisasi:**
    *   Menuliskan visi dan misi resmi dari organisasi tempat pelaksanaan PKL.
*   **2.3. Struktur Organisasi:**
    *   Menjelaskan bagan struktur organisasi perusahaan dan posisi tim PKL di dalamnya (direpresentasikan dalam bentuk diagram).
    *   **Constraint Visual Khusus:** Pada gambar diagram struktur organisasi, **wajib memberikan penekanan (*highlight*)** pada unit atau divisi tempat pelaksanaan PKL dengan menggunakan **efek bayangan (*shading*) atau kotak bergaris putus-putus (*dashed lines*)**.
*   **2.4. Deskripsi Pekerjaan:**
    *   Menjelaskan setiap tahap pekerjaan yang dilakukan mahasiswa terkait divisinya dan mengaitkannya dengan proyek PKL.
    *   **Constraint Kronologis:** Pekerjaan dijelaskan berdasarkan rentang waktu dari **tanggal mulai sampai tanggal berakhirnya PKL**.
    *   *Fitur Fleksibilitas:* Mahasiswa diperbolehkan menuliskan seluruh pekerjaan tambahan selama PKL meskipun tidak terlalu berhubungan langsung dengan proyek utama PKL.
*   **2.5. Jadwal Kerja:**
    *   Menjelaskan waktu pelaksanaan PKL, jam kerja harian, serta rentang tanggal bekerja (termasuk mencantumkan jika terdapat hari libur nasional).
    *   **Constraint Durasi Wajib:** Waktu pelaksanaan PKL adalah sebanyak **25 hingga 40 hari kerja**.
    *   *Keterkaitan:* Rincian jadwal ini mengacu langsung pada **Lampiran B (Log Sheet)**.

### Bab III: Landasan Teori
Menjelaskan konsep dan dasar teori yang digunakan dalam implementasi sistem, aplikasi, atau *prototype*.
*   **3.1. Dasar Teori:**
    *   **Constraint Sumber Referensi (Allowed Sources):** Wajib menggunakan data dari buku, jurnal referensi, publikasi tugas akhir, laporan penelitian, dan informasi situs web resmi yang dapat dipertanggungjawabkan.
    *   **Constraint Larangan Sumber (Prohibited Sources):** **Hindari/Dilarang** menggunakan dasar teori yang bersumber dari tautan **Wikipedia, surat kabar, atau portal berita**, karena berpotensi memuat isi yang tidak bersifat fakta ilmiah.
*   **3.2. Teori I, 3.3. Teori II, dst.:**
    *   Mendeskripsikan teori/konsep acuan dan wajib disertai **pembahasan sederhana mengenai bagaimana teori tersebut digunakan/diterapkan** di dalam laporan PKL yang dikerjakan.
*   **Fitur Penomoran Sub-Teori:**
    *   Untuk penjabaran di bawah subbab teori (misal: `3.3.1. Sub Teori I`), wajib menggunakan **level penomoran 3** dengan format gaya dokumen (*Word Style*) **`"Heading 3"`**.

### Bab IV: Metode Penelitian
Menjelaskan pelaksanaan teknis PKL. *Catatan Fitur: Struktur subbab pada Bab IV bersifat adaptif dan dapat disesuaikan kembali dengan jenis output yang dikerjakan di tempat PKL.*
*   **4.1. Analisis Permasalahan:**
    *   Berisi analisis persoalan yang harus diselesaikan beserta usulan solusinya (disesuaikan dengan latar belakang, deskripsi masalah, batasan PKL, dan teknologi pendukung).
*   **4.2. Alur Penyelesaian:**
    *   Menjelaskan tahapan penyelesaian secara detail mulai dari:
        1. Observasi,
        2. Identifikasi masalah,
        3. Perumusan masalah,
        4. Pemilihan metode,
        5. Implementasi,
        6. Pengujian, hingga
        7. Penarikan kesimpulan.
    *   *Rekomendasi Visual:* Disarankan menggunakan diagram alir (**flowchart**) agar tergambar dengan jelas.
*   **4.3. Gambaran Umum Sistem/Aplikasi/Prototype:**
    *   Menggambarkan arsitektur umum dari sistem/aplikasi/*prototype* yang dikembangkan dengan bantuan diagram atau gambar ilustrasi.
*   **4.4. Alat dan Bahan:**
    *   **4.4.1. Alat:** Menguraikan spesifikasi perangkat keras (PC, Notebook, Smartphone, Arduino, Raspberry Pi, dsb.) serta perangkat lunak (*Software*) yang digunakan.
    *   **4.4.2. Bahan:** Menguraikan data atau materi pendukung. Diizinkan menggunakan salah satu atau kombinasi dari 3 kategori dataset berikut:
        1. Dataset pihak pertama yang diperoleh langsung melalui izin instansi.
        2. Dataset pihak lain yang diperoleh dengan izin atau di bawah lisensi yang mengizinkan penggunaan langsung.
        3. Dataset pihak pertama yang disusun/dikumpulkan sendiri melalui kuesioner, observasi, atau wawancara (*interview*).
*   **4.5. Metodologi Pengembangan:**
    *   Menguraikan secara detail metodologi pembangunan sistem/*prototype*, meliputi: alur pengembangan (misal SDLC: Agile, Waterfall, dll.), desain/diagram sistem, rencana pengembangan, cara pengumpulan data, hingga rancangan *low/high fidelity*.

### Bab V: Hasil Implementasi
Menjelaskan hasil perancangan serta batasan lingkup implementasi yang dikerjakan.
*   **5.1. Hasil Implementasi:**
    *   Menampilkan hasil dari proses pengembangan.
    *   **Constraint Pengujian:** Wajib menuliskan **hasil pengujian dari semua fitur** yang telah dirancang pada Bab IV berdasarkan metodologi yang digunakan.
*   **5.2. Evaluasi dan Analisis:**
    *   Menuliskan evaluasi dan analisis sederhana (dapat berbentuk tabel, visualisasi data, atau narasi) berdasarkan hasil implementasi dan pengujian.
    *   *Fitur Konten Evaluasi:* Dapat menceritakan hasil presentasi akhir di hadapan instansi bersangkutan, termasuk menyebutkan **siapa saja *stakeholder* yang terlibat** serta **tanggal pelaksanaan presentasi**.

### Bab VI: Kesimpulan dan Saran
Bagian penutup dari laporan utama.
*   **6.1. Kesimpulan:**
    *   Wajib memuat kesimpulan mengenai **dua hal**: (1) proses pelaksanaan PKL secara umum, dan (2) substansi teknis yang dikerjakan.
    *   **Constraint Keterkaitan Mutlak:** Kesimpulan **harus menjawab semua poin Rumusan Masalah** dan **harus sesuai dengan Tujuan** yang telah didefinisikan pada Bab I.
*   **6.2. Saran:**
    *   Berisi saran pengembangan penelitian ke depannya (berdasarkan observasi dan analisis hasil), serta saran terkait proses pelaksanaan teknis PKL selama bekerja di instansi agar lebih baik di masa mendatang.

---

## 4. Bagian Akhir & Lampiran (Back Matter & Appendices)

### Referensi (Daftar Pustaka)
*   **Posisi Letak:** Diletakkan tepat setelah Bab VI Kesimpulan dan sebelum bagian Lampiran.
*   **Format & Pengurutan:**
    *   Ditulis menggunakan gaya sitasi **IEEE** dengan penomoran berurut mulai dari `[1]`.
    *   **Constraint Pengurutan Khusus:** Daftar referensi **diurutkan berdasarkan abjad (alfabetis) dari nama pengarang**, kemudian diberi nomor urut mulai dari `[1]`.
*   **Constraint Jumlah & Kuota Sumber (Strict Quota):**
    *   Jumlah total referensi **minimal 10 sumber**.
    *   Diperbolehkan mengambil referensi dari situs web (*website*), tetapi **dibatasi maksimal hanya 3 referensi website**. (Artinya, minimal 7 referensi lainnya wajib berasal dari jurnal, buku, prosiding, atau publikasi ilmiah resmi).

### Lampiran A: TOR (Term of Reference)
*   **Status:** **Wajib** bagi seluruh mahasiswa PKL.
*   **Fungsi & Waktu Pembuatan:** Berisi *job description* dan target PKL yang disepakati bersama antara Mahasiswa dan Perusahaan. Dibuat pada **awal pelaksanaan PKL**.
*   **Struktur Sub-bagian Wajib dalam TOR:**
    1. Penjabaran
    2. Latar Belakang
    3. Tujuan Pekerjaan
    4. Lingkup Pekerjaan
    5. Metodologi
    6. Hasil Pekerjaan
    7. Jadwal Kerja
    8. Lain-lain
    9. Kerahasiaan dan Perlindungan Informasi
*   **Constraint Pengesahan TOR (3 Pihak Penandatangan):**
    1. **Pihak Mahasiswa:** Tanda tangan, Nama Mahasiswa, NIM.
    2. **Pihak Instansi (Pembimbing):** Tanda tangan & cap basah/resmi, Nama Pembimbing Lapangan/Jabatan, Nomor Pegawai.
    3. **Pihak Instansi (Atasan):** Tanda tangan & cap basah/resmi, Nama Atasan/Jabatan, Nomor Pegawai.

### Lampiran B: Log Sheet
*   **Isi:** Melampirkan dokumen **Form Presensi & Logsheet (Formulir KP2)**.
*   **Constraint Legalitas:** Formulir wajib sudah **ditandatangani dan diberi cap resmi** oleh pihak instansi.
*   **Fitur Tabel:** Panjang tabel *Log Sheet* bersifat dinamis menyesuaikan dengan jumlah hari kerja pelaksanaan PKL (25–40 hari kerja).

### Lampiran C: Dokumen Teknik
*   **Isi:** Melampirkan dokumen teknis hasil pelaksanaan PKL, seperti *Software Requirement Specification* (SRS), *Manual Book* (Buku Panduan Pengguna), potongan Kode Program (*Source Code*), dll.
*   **Status & Constraint Kerahasiaan (*Confidentiality Clause*):**
    *   Lampiran ini bersifat **wajib ada**.
    *   **Pengecualian (*Exception Handling*):** Jika pihak perusahaan menyatakan bahwa dokumen teknis terkait proyek PKL bersifat rahasia (*confidential*), maka isi Lampiran C **wajib diganti dengan Surat Pernyataan Resmi dari Perusahaan** yang ditandatangani oleh pembimbing di perusahaan, yang menyatakan bahwa dokumen teknis terkait PKL tersebut bersifat *confidential*.

### Lampiran D: Dokumentasi Kegiatan
*   **Isi & Bentuk Media:**
    *   Berisi bukti visual kegiatan pelaksanaan PKL.
    *   Dapat berupa foto kegiatan langsung (*offline*), tangkapan layar/*screenshot* kegiatan (jika PKL dilaksanakan secara *remote*/*online*), atau kombinasi keduanya.
    *   Dapat juga menyertakan dokumentasi dalam bentuk video dengan mencantumkan **tautan (link) YouTube**.
*   **Constraint Frekuensi Wajib:** Foto dokumentasi **wajib ada untuk setiap minggunya** (dikelompokkan per minggu dengan format header: `Minggu 1 (<Tanggal>-<Bulan>-<Tahun>)`, `Minggu 2 (...)`, dst., lengkap dengan *caption* `Gambar D.1.`, dst.).