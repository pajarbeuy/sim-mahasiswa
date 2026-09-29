# README.md
# Sistem Informasi Mahasiswa (SIM)
Modul Praktikum Pemrograman Python
15
Aplikasi console-based untuk mengelola data mahasiswa
pada Program Studi Sistem Informasi.
## Identitas
- Nama: [Nama Lengkap]
- NIM: [NIM Anda]
- Kelas: [Kelas Praktikum]
## Fitur
- Tambah data mahasiswa (NIM, nama, prodi, angkatan, IPK)
- Tampilkan seluruh data dalam tabel
- Cari mahasiswa berdasarkan NIM
- Hapus data mahasiswa
- Validasi data input
## Prasyarat
- Python 3.10+
- pip
## Instalasi
\`\`\`bash
git clone https://github.com/USERNAME/sim-mahasiswa.git
cd sim-mahasiswa
python3 -m venv venv
source venv/bin/activate # Linux/macOS
pip install -r requirements.txt
\`\`\`
## Penggunaan
\`\`\`bash
python -m src.main
\`\`\`
## Pengujian
\`\`\`bash
pytest tests/ -v
\`\`\`
## Struktur Proyek
- src/models.py — Model data Mahasiswa
- src/main.py — Program utama & menu
- tests/ — Unit test
## Setup Checklist
- [x] Python terinstal (versi: ___)
- [x] Virtual environment dibuat & diaktivasi
- [x] Paket terinstal via requirements.txt
- [x] Program berjalan tanpa error
- [x] Unit test lulus
- [x] Repositori Git diinisiasi
- [x] Push ke GitHub berhasil
- [x] README.md lengkap