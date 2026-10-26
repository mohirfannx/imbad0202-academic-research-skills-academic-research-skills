# Panduan skripsi: vermikompos dan jagung manis

Penyesuaian berbahasa Indonesia untuk penelitian pertumbuhan vegetatif dan biomassa jagung manis pada Ultisol, dengan pengamatan kimia tanah, respirasi, dan bakteri yang dapat dikultur pada Nutrient Agar (NA).

Ini adalah panduan proyek dan satu perintah pembantu untuk empat skill ARS yang sudah ada, bukan mode baru. Profil penelitian lengkap tetap berasal dari dokumen terbaru pengguna.

## Mulai

1. Baca [alur kerja skripsi](docs/skripsi/ALUR_KERJA.md).
2. Salin [template profil privat](docs/skripsi/PROFIL_PRIVAT.template.md) ke `.context/skripsi/PROFIL.md` di checkout lokal, lalu isi dari proposal, denah, dan jadwal pemupukan terbaru.
3. Simpan bahan dan keluaran privat di `.context/skripsi/`. Folder `.context/` sudah diabaikan oleh Git di repositori ini. Jangan memaksa menambahkan isinya ke Git.
4. Pada instalasi plugin Claude Code yang memuat direktori `commands/`, pilih perintah `ars-skripsi` (namespace mengikuti instalasi). Perintah ini perlu dimuat ulang apabila host masih memakai versi plugin lama.
5. Untuk ChatGPT dengan konektor GitHub, gunakan prompt biasa berikut dan berikan akses ke bahan privat yang diperlukan:

> Baca SKRIPSI.md, docs/skripsi/ALUR_KERJA.md, dan docs/skripsi/CHECKLIST.md di repositori ini. Terapkan panduan untuk merevisi Bab I berdasarkan dokumen penelitian terbaru yang saya berikan. Mulai dengan memeriksa konsistensi tujuan, perlakuan, dan batas kesimpulan.

Menambahkan file ke GitHub tidak otomatis memasang skill atau mengaktifkan perintah dalam ChatGPT. Jika belum memasang ARS pada host yang mendukungnya, lihat [Quick Start](QUICKSTART.md) dan [Setup](docs/SETUP.md). Panduan ini juga dapat digunakan sebagai instruksi biasa tanpa menjalankan pipeline penuh.

## Pekerjaan yang tersedia

| Kebutuhan | Hasil yang diminta |
|---|---|
| Audit Bab I–III | Daftar konflik beserta sumber dan usulan perbaikan |
| Revisi Bab I | Latar belakang sampai hipotesis yang konsisten |
| Tinjauan pustaka | Matriks bukti dan sintesis sesuai parameter penelitian |
| Audit metode | Unit percobaan, pengambilan contoh, prosedur, dan rencana analisis |
| Pemeriksaan hasil | Audit satuan, perhitungan, asumsi analisis, dan batas interpretasi |
| Revisi bahasa | Naskah ilmiah Indonesia yang ringkas, jelas, dan setia pada bukti |

## Batas penelitian

- Fokus pada pertumbuhan vegetatif dan biomassa; jangan menyimpulkan hasil panen tongkol dari parameter tersebut.
- Perbandingan kompos tanpa pupuk tambahan versus vermikompos berpupuk menilai paket perlakuan. Pengaruh dosis vermikompos dinilai di antara dosis dengan pemupukan sama.
- TPC pada NA melaporkan bakteri yang dapat dikultur pada kondisi uji, bukan keseluruhan mikroba atau keanekaragaman tanah.
- Hasil penelitian, angka dosis, jadwal perusahaan, identitas pribadi, dan naskah lengkap tidak disertakan dalam panduan publik ini.

Panduan disusun dengan mengacu pada Bab I revisi dan template tugas akhir yang disediakan pengguna pada 26 Oktober 2026. Ini bukan penetapan kebijakan resmi kampus. Gunakan template terbaru pengguna untuk setiap penyusunan naskah.
