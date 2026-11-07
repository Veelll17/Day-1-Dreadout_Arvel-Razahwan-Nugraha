# Day-1-Dreadout_Arvel-Razahwan-Nugraha

> **Dokumentasi Kegiatan Workshop Day 1 â€“ TIKMENGAJAR 2026**  
> *"From AI to GitHub: Building with AI, Managing Change with GitHub"*  
> **Jurusan Teknik Informatika dan Komputer (TIK) â€“ Politeknik Negeri Jakarta**

---

## ðŸ“Œ Identitas Peserta

| Keterangan | Rincian |
| :--- | :--- |
| **Nama Lengkap** | Arvel Razahwan Nugraha |
| **Kelompok** | Dreadout (Kelompok 20) |
| **Program Studi / Jurusan** | Teknik Informatika dan Komputer (TIK) |
| **Institusi** | Politeknik Negeri Jakarta (PNJ) |
| **Akun GitHub** | [@Veelll17](https://github.com/Veelll17) |
| **Tautan Repository** | [Day-1-Dreadout_Arvel-Razahwan-Nugraha](https://github.com/Veelll17/Day-1-Dreadout_Arvel-Razahwan-Nugraha) |
| **Hari / Tanggal** | Sabtu, 7 November 2026 |

---

## ðŸ“– Deskripsi Singkat Mengenai Repository

Repository ini dibuat sebagai wadah dokumentasi resmi penugasan **Misi Proyek Workshop Day 1** pada kegiatan **TIKMENGAJAR 2026** Himpunan Mahasiswa Informatika dan Komputer (HIMATIK) Politeknik Negeri Jakarta. 

Repository ini memuat seluruh materi pembelajaran, catatan teknis, rangkuman konsep *Prompt Engineering*, pengenalan dan alur kerja *Version Control System* menggunakan Git & GitHub, setup lingkungan kerja, praktik pembuatan aplikasi *Student Task Planner*, serta refleksi dan pandangan pribadi mengenai kegiatan workshop.

---

## ðŸŽ¯ Tujuan Repository

1. **Memenuhi Ketentuan Penugasan Misi Day 1**: Memenuhi ketentuan tugas individu Proyek Workshop Day 1 TIKMENGAJAR 2026 sesuai dengan standar dan rubrik penilaian yang ditentukan panitia.
2. **Penyimpanan & Dokumentasi Terstruktur**: Memanfaatkan GitHub sebagai media penyimpanan (*cloud storage*), pengelolaan, dan publikasi catatan serta kode secara terstruktur dan daring.
3. **Penerapan Version Controlling**: Mengimplementasikan secara langsung konsep dasar Git (seperti `init`, `add`, `commit`, dan `push`) ke platform remote repository GitHub dengan visibilitas *Public*.
4. **Referensi Belajar Mandiri**: Menjadi catatan komprehensif dan bahan referensi yang dapat dibuka kembali di masa depan dalam menempuh perkuliahan di Jurusan TIK PNJ.

---

## â„¹ï¸ Informasi Kegiatan Workshop yang Didokumentasikan

| Komponen | Penjelasan |
| :--- | :--- |
| **Nama Kegiatan** | Workshop Day 1 Proyek TIKMENGAJAR 2026 |
| **Judul Materi** | *From AI to GitHub: Building with AI, Managing Change with GitHub* |
| **Narasumber / Pemateri**| **Nugi Farhan** (Senior Product Designer) |
| **Waktu Pelaksanaan** | Sabtu, 7 November 2026 |
| **Penyelenggara** | Divisi Pendidikan dan Pelatihan (DIKTEK) HIMATIK PNJ |
| **Fokus Topik** | 1. Membangun dan mengembangkan produk/aplikasi berbantuan AI (*Prompt Engineering*)<br>2. Manajemen perubahan dan kolaborasi kode (*Git & GitHub*) |
| **Proyek Praktik** | *Student Task Planner* (Aplikasi Web Sederhana untuk Mahasiswa Baru) |

### Capaian Pembelajaran Workshop (Target Objektif)
1. Mahasiswa mampu memahami dan menjelaskan bagaimana prompt AI yang spesifik dan kontekstual menghasilkan output kode yang jauh lebih baik dan relevan.
2. Mahasiswa mampu mengidentifikasi dan membedakan peran antara sistem **Git** (lokal) dan platform **GitHub** (remote / web).
3. Mahasiswa memahami komponen inti manajemen repositori: *Repository*, *Commit*, *Branch*, dan *Pull Request*.
4. Mahasiswa mampu mempraktikkan alur kerja *Version Controlling* secara mandiri.

---

## ðŸ“š Rangkuman Materi Workshop

### 1. Prompt Engineering: Membangun dengan Bantuan AI

#### A. Definisi Prompt dan Prompt Engineering
- **Prompt**: Instruksi, konteks, pertanyaan, atau masukan yang diberikan kepada *Large Language Model* (LLM) untuk memperoleh respons tertentu (teks, kode, analisis, dsb.).
- **Prompt Engineering**: Teknik merancang instruksi yang sistematis, presisi, dan kontekstual agar AI menghasilkan keluaran yang akurat, relevan, terstruktur, dan siap digunakan (*production-ready*).

#### B. Konsep "Context is Key"
Prompt tanpa konteks (misal: `"Create student task planner"`) menghasilkan output yang generik, terlalu luas, atau tidak sesuai kebutuhan spesifik. Sebaliknya, prompt dengan konteks yang lengkap memberikan batasan teknis (*constraints*) dan format yang diharapkan.

#### C. Struktur Anatomi Prompt yang Efektif
Sebuah prompt profesional sekurang-kurangnya memiliki 4 elemen utama:
1. **Role (Peran)**: Memberikan identitas peran kepada AI.  
   *Contoh:* *"You are helping me build a beginner-friendly student task planner as a simple web application."*
2. **Task / Goal (Tujuan)**: Menjelaskan apa yang ingin dicapai secara spesifik.  
   *Contoh:* *"Create a task planner that helps first-year university students keep track of assignments and deadlines."*
3. **Context & Constraints (Kebutuhan & Batasan)**:  
   - Fitur utama: Daftar tugas, tanggal tenggat (*deadline*), status selesai (*completed*), filter status (*all/pending/completed*), desain responsif.
   - Batasan teknis: Menggunakan HTML, CSS, dan Vanilla JavaScript tanpa *external dependencies* atau *libraries*. Kode harus rapi dan memiliki penjelasan.
4. **Format & Verification (Bentuk Output & Validasi)**:  
   Menentukan cara AI menyajikan hasil serta mewajibkan verifikasi.  
   *Contoh:* *"Provide the complete code for each file, explain how to run the application, and describe how to test the main interactions. Do not claim that the application works until you have verified its behavior."*

#### D. Taktik Penulisan Prompt Berkualitas
- **Kata Kerja Aksi**: Gunakan kata kerja imperatif seperti *Buatkan*, *Rancang*, *Analisis*, *Uraikan*.
- **Batasan Format**: Tentukan panjang output, struktur penamaan file, dan gaya penulisan kode.
- **Target Audiens**: Beri tahu siapa audiens pengguna aplikasi/dokumen.
- **Keuntungan**: Meningkatkan performa model, meminimalisir halusinasi/bias, serta memaksimalkan kendali pengembang atas hasil rancangan.

---

### 2. Git & GitHub: Manajemen Perubahan dan Kolaborasi

#### A. Memahami Perbedaan Git dan GitHub

| Aspek | Git | GitHub |
| :--- | :--- | :--- |
| **Pengertian** | *Distributed Version Control System* (DVCS) perangkat lunak bebas yang dijalankan secara lokal di komputer pengembang. | Platform *cloud-based* berbasis web untuk menyimpan, membagikan, dan mengelola repository Git secara online. |
| **Pencipta / Peluncuran** | Diciptakan oleh **Linus Torvalds** pada tahun 2005. | Didirikan pada tahun 2008 (kini bagian dari Microsoft). |
| **Fungsi Utama** | Melacak histori riwayat perubahan file, cabang (*branching*), dan *snapshot* kode secara offline/lokal. | Kolaborasi tim, *code review*, penyimpanan remote (*cloud*), pelacakan issue, CI/CD, dan publikasi proyek open-source. |

#### B. Siklus Area Kerja Git (*Git Workflow*)
Perubahan dalam Git dikelola melalui 3 zona utama:
```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”       git add        â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”      git commit      â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚   Working Directory   â”‚  â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€>  â”‚  Staging Area (Index) â”‚  â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€>  â”‚ Git Directory (.git)  â”‚
â”‚   (File di Komputer)  â”‚                      â”‚ (Perubahan Terpilih)  â”‚                      â”‚ (Repository Lokal)    â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜                      â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜                      â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```
1. **Working Directory**: Folder fisik di komputer tempat file diedit dan dimodifikasi secara aktif.
2. **Staging Area (Index)**: Zona persiapan untuk menyeleksi file mana saja yang siap disimpan ke dalam *commit* berikutnya.
3. **Git Directory / Repository**: Database lokal (.git) tempat seluruh riwayat dan *snapshot commit* tersimpan secara permanen.

#### C. Perintah Esensial Git
- `git init`: Menginisialisasi repositori Git baru di direktori kerja lokal.
- `git add <file>` / `git add .`: Memindahkan file yang dimodifikasi ke Staging Area.
- `git commit -m "<pesan>"`: Mengabadikan *snapshot* perubahan dari Staging Area ke riwayat repositori lokal dengan pesan penjelasan.
- `git remote add origin <url>`: Menautkan repositori lokal ke remote repository (GitHub).
- `git push -u origin <branch>`: Mengirim seluruh commit dari branch lokal ke remote GitHub.
- `git pull origin <branch>`: Menarik perubahan terbaru dari repository remote dan menggabungkannya ke branch lokal.

#### D. Pengaturan Lingkungan Kerja (*Environment Setup*)
1. **Konfigurasi Identitas Global**:
   ```bash
   git config --global user.name "Arvel Razahwan Nugraha"
   git config --global user.email "arvelrazahwannugraha@gmail.com"
   ```
2. **Setup VS Code**: Memastikan integrasi command `code` pada *System PATH* untuk efisiensi terminal.
3. **Autentikasi Aman via SSH Key (Ed25519)**:
   - Dibuat menggunakan algoritma kriptografi modern:
     ```bash
     ssh-keygen -t ed25519 -C "arvelrazahwannugraha@gmail.com"
     ```
   - Public key ditambahkan ke akun GitHub (*Settings -> SSH and GPG keys*).
   - Verifikasi koneksi aman ke GitHub:
     ```bash
     ssh -T git@github.com
     # Respons sukses: "Hi username! You've successfully authenticated, but GitHub does not provide shell access."
     ```

---

### 3. Praktik Proyek: Student Task Planner

Dalam workshop dipraktikkan alur kerja pengembangan modern dengan skenario pembuatan aplikasi **Student Task Planner**:
1. Menentukan rancangan dan kebutuhan aplikasi web sederhana untuk pencatatan tugas kuliah mahasiswa.
2. Menggunakan platform AI (*Claude / Antigravity / ChatGPT*) dengan metode *Structured Prompting*.
3. Menyusun file proyek (`index.html`, `style.css`, `app.js`).
4. Menginisialisasi repositori lokal dengan `git init`.
5. Melakukan *staging* dan *commit* awal (*Initial commit*).
6. Menghubungkan repositori lokal ke repositori GitHub.
7. Mendorong (*push*) commit ke branch `main`.
8. Melakukan pembaharuan kode dan mendokumentasikan setiap perubahan dengan commit yang bermakna (*meaningful commit message*).

---

## ðŸ’¡ Poin-Poin Penting & Pengetahuan Baru

Beberapa wawasan utama yang didapatkan melalui sesi workshop ini antara lain:

1. **Efektivitas Prompt Berbasis Kerangka Kerja (*Framework*)**: Kualitas keluaran dari model AI berbanding lurus dengan kejelasan instruksi yang diberikan. Menerapkan struktur **Role, Task, Context, Format** mengeliminasi ambigu dan mempercepat proses *development*.
2. **Pentingnya Verifikasi Kritis terhadap Kode AI**: AI merupakan alat bantu akselerasi, bukan pengganti logika berpikir kritis. Setiap potongan kode yang digenerate harus dibaca, dipahami, dan diuji secara menyeluruh (*testing & verification*).
3. **Arsitektur Tiga Zona Git**: Memahami perbedaan antara *working directory*, *staging area*, dan *local repository* memberikan kendali penuh dalam mengelompokkan revisi kode sebelum dijadikan commit resmi.
4. **Keamanan Autentikasi Modern**: Memahami manfaat penggunaan algoritma kunci **Ed25519** untuk komunikasi aman tanpa perlu berulang kali memasukkan kredensial login akun secara manual.
5. **Budaya Dokumentasi yang Baik**: Menulis `README.md` yang rapi dan komprehensif adalah cerminan profesionalisme seorang *software engineer*. README merupakan etalase utama yang pertama kali dilihat oleh kolaborator maupun calon perekrut.

---

## ðŸ’¬ Pendapat Pribadi tentang Day 1 Proyek Workshop

> Mengikuti kegiatan **Day 1 Proyek Workshop TIKMENGAJAR 2026** memberikan pengalaman yang sangat berharga dan membuka wawasan baru bagi saya sebagai mahasiswa baru di Jurusan Teknik Informatika dan Komputer Politeknik Negeri Jakarta.
>
> **Kesan dan Evaluasi Materi:**  
> Materi yang dibawakan oleh Kak **Nugi Farhan** sangat relevan dengan dinamika industri teknologi masa kini. Penjelasan mengenai *Prompt Engineering* tidak sekadar mengajarkan "cara bertanya ke AI", melainkan bagaimana cara berpikir terstruktur, merumuskan batasan masalah, serta memanfaatkan *Generative AI* sebagai *copilot* untuk meningkatkan produktivitas tanpa kehilangan pemahaman mendasar terhadap kode yang dibuat.
>
> Di sisi lain, pembahasan **Git & GitHub** disajikan secara lugas dan aplikatif. Konsep *version control* yang awalnya terkesan rumit dapat dipahami dengan mudah melalui visualisasi alur *working tree*, *staging area*, hingga proses sinkronisasi ke repositori daring. Praktik langsung membuat dan mengelola repositori tugas ini memberikan fondasi yang kuat bagi saya untuk menghadapi berbagai mata kuliah pemrograman, proyek berbasis tim (*PBL/PjBL*), serta kultur kolaborasi software engineering di masa depan.
>
> Secara keseluruhan, kegiatan Workshop Day 1 ini sangat terorganisir, interaktif, dan berhasil membekali mahasiswa baru dengan keterampilan fundamental yang esensial untuk berkembang di dunia IT.

---

## ðŸ—‚ï¸ Struktur Direktori Repository

```text
Day-1-Dreadout_Arvel-Razahwan-Nugraha/
â”œâ”€â”€ README.md               # Dokumentasi lengkap kegiatan workshop (file utama)
â””â”€â”€ assets/                 # (Opsional) Tempat aset visual, diagram, atau tangkapan layar pendukung
```

---

## âœ… Checklist Pemenuhan Ketentuan Tugas

Berikut adalah daftar periksa kesesuaian tugas terhadap seluruh ketentuan yang ditetapkan panitia pada website Expectik:

- [x] **Akun GitHub Aktif**: Memiliki akun GitHub aktif atas nama [@Veelll17](https://github.com/Veelll17).
- [x] **Repository Baru**: Repositori dibuat baru khusus untuk penugasan Day 1.
- [x] **Visibilitas Public**: Repositori berstatus *Public* dan dapat diakses terbuka oleh panitia.
- [x] **Format Nama Sesuai Ketentuan**: `Day-1-Dreadout_Arvel-Razahwan-Nugraha` (Format: `Day-1-(Nama_Kelompok)_Nama Lengkap`).
- [x] **Kelengkapan Isi README.md**:
  - [x] Nama lengkap peserta (**Arvel Razahwan Nugraha**)
  - [x] Deskripsi singkat mengenai repository
  - [x] Tujuan atau kegunaan repository
  - [x] Informasi lengkap kegiatan workshop
- [x] **Dokumentasi Kegiatan Workshop**:
  - [x] Rangkuman materi yang disampaikan pemateri
  - [x] Poin-poin penting dan pengetahuan baru yang dipelajari
  - [x] **Pendapat pribadi tentang Day 1 Proyek Workshop**
- [x] **Kerapihan & Struktur**: Seluruh dokumen disusun rapi dan terstruktur menggunakan standar GitHub-Flavored Markdown.
- [x] **Tautan Valid**: Tautan repository siap dikumpulkan melalui mekanisme pengumpulan resmi website Expectik sebelum batas waktu (Sabtu, 7 November 2026 pukul 23.59 WIB).

---

<p align="center">
  <b>TIKMENGAJAR 2026 â€¢ Himpunan Mahasiswa Informatika dan Komputer (HIMATIK) â€¢ Politeknik Negeri Jakarta</b><br>
  <i>"Kenali Potensimu, Temukan Arahmu, Berkembang Bersama TIK"</i>
</p>
