TUJUAN BARU: Adiwiyata Ekotheologis
Memperluas panel Adiwiyata dengan tiga jenis laporan:
1. Sampah botol: jumlah botol (per buah), akumulasi menjadi poin kelas (rombel).
2. Sampah kertas: akumulasi menjadi poin kelas. Satuannya (lembar / kg / tumpukan) BELUM diputuskan.
3. Sampah MBG organik untuk kompos. Berat standar per siswa:
   - kulit semangka 90 g
   - kulit pisang 50 g
   - kulit + isi kelengkeng 50 g
   - kulit jeruk 60 g
   Berat total = berat standar × jumlah siswa yang membuang. Setiap 10 kg butuh larutan EM4 (takaran per 10 kg BELUM ditetapkan; usulan bawaan 1 liter larutan = 10 ml EM4 + 10 ml molase per liter air, dapat diubah di pengaturan).

Alur: siswa melapor ke akun pemilik/guru (status "menunggu"), guru/kader menyetujui, lalu poin masuk ke rombel (tidak mengubah poin/bintang pribadi). Semua terekap di laporan admin/pemilik/guru yang ditunjuk pemilik, bisa diunduh CSV.
Ide tambahan: siswa memotret kulit buah, AI penglihat gambar di server (memakai slot penyedia AI yang sudah ada) mengenali jenisnya lalu menampilkan info dan berat standar. Berat itu perkiraan, siswa/guru bisa mengoreksi jenis, dan guru mengonfirmasi.

KEPUTUSAN ARSITEKTUR (sudah disepakati arahnya)
- Satu aplikasi, satu akun, satu Sheet. Adiwiyata dibuat sebagai RUANG 3D KEDUA ("Eco-Gazebo Classroom"), dimuat hanya saat dimasuki lewat pintu/portal dari kelas, supaya HP tetap ringan. Aplikasi kompos menjadi modul di dalam Adiwiyata, bukan aplikasi terpisah.
- Referensi visual ruang (dua gambar terlampir): gazebo bambu-kayu berbentuk lengkung, atap hijau hidup dengan panel surya, deck kayu dengan meja belajar, papan nama "The Eco-Gazebo Classroom — Sustainability in Action", Smart Recycling Hub 4 tong (kertas, plastik/botol, kompos, residu) dengan kios QR, kolam wetland bioswale, bedeng sayur, jalan setapak berkerikil, bangku kayu.

TAHAPAN YANG DIUSULKAN
A. Menu Adiwiyata + lapor botol & kertas + persetujuan guru (perlu perubahan code.gs: jenis berbasis "buah" selain "kg").
B. Lapor kompos MBG, kalkulator berat total & kebutuhan EM4, pengaturan berat standar yang bisa diubah pemilik.
C. Foto kulit buah dikenali AI + koreksi manual + konfirmasi guru.
D. Ruang 3D Eco-Gazebo (portal, Smart Recycling Hub interaktif, papan poin rombel di dinding, kolam dan kebun sebagai dekorasi/animasi ringan).

IDE KREATIF
- Tiap tong di Recycling Hub bisa diklik: klik tong botol membuka form lapor botol, tong kompos membuka form MBG (cukup satu antarmuka, tanpa menu rumit).
- "Kebun naik level": semakin tinggi poin Adiwiyata rombel bulan ini, tanaman di bedeng dan atap hijau gazebo makin rimbun (visual progres, bukan angka saja).
- Misi mingguan ekotheologis: ayat/hadis singkat tentang menjaga bumi (mis. kebersihan, tidak berlebihan) sebagai "renungan" yang muncul saat siswa selesai lapor, selaras Kurikulum Berbasis Cinta.
- Papan "Rombel Terhijau" bulanan, dengan lencana untuk kader terajin.
- Hasil kompos: grafik total kg MBG yang terkompos dan perkiraan liter EM4 terpakai, tampil di papan dinding gazebo.
- Setelah kompos matang, catat panen kompos dan pemakaiannya untuk bedeng sayur sekolah (siklus tertutup).

YANG PERLU DISIAPKAN DI PERCAKAPAN BARU
- File index_uji_v0.17.0.html dan code.gs UJI terbaru (code.gs belum pernah saya lampirkan di percakapan ini).
- Dua gambar referensi (samping_depan.jpg dan atas.jpg).
- Jawaban dua keputusan terbuka: satuan kertas, dan takaran EM4 per 10 kg.
Mulai dari Tahap A.
