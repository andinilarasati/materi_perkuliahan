## Intelligent Agent

- Perangkat lunak atau sistem yang bekerja otomatis tanpa campur tangan manusia.
- Berfungsi untuk navigasi, pengambilan keputusan, dan otomatisasi tugas.
- Contoh: spam filter (Gmail), antivirus SmadAV, shopping assistant pada e-commerce.

## Contoh Penerapan Intelligent Agent

- Autonomous agent: pengereman otomatis pada mobil (sensor GPS, kamera, odometer).
- Diagnostic agent: bidang medis (input gejala → output diagnosis).
- Part-picking robot: mengambil benda pada conveyor dengan sensor kamera dan lengan robot.

## Tipe-Tipe Intelligent Agent

- Simple Reflex Agent: merespons langsung berdasarkan kondisi.
- Model-Based Reflex Agent: menggunakan model internal untuk menangani lingkungan kompleks.
- Goal-Based Agent: bertindak untuk mencapai tujuan tertentu.

- Utility-Based Agent: memilih aksi terbaik berdasarkan nilai utilitas.
- Learning Agent: belajar dari pengalaman, evaluasi diri, dan perbaikan kinerja.

## Cara Kerja Agent

- Harus rasional dan sesuai dengan tujuan.
- Mampu menangkap pesan dari lingkungan.
- Performa diukur secara objektif.
- Sukses bila tindakan menghasilkan hasil sesuai harapan.

## Contoh Nyata Penggunaan Agent

- Penjualan online: otomatisasi pengiriman, negosiasi dengan supplier, analisis tren.
- Help desk customer: menjawab keluhan pelanggan secara otomatis.
- Web browser: merekam histori dan preferensi pencarian.
- Shopping assistant: memberikan rekomendasi produk dan pengingat belanja.

## Masalah dan Ruang Keadaan

- Sistem AI membutuhkan basis pengetahuan dan motor inferensi.
- Masalah direpresentasikan dalam ruang keadaan (state space) yang mencakup initial state, goal state, dan aturan transisi.

## Representasi Masalah

- Graph Keadaan: node menunjukkan state, arc menunjukkan transisi.
- Pohon Pencarian: representasi hirarkis dari state.
- Pohon AND/OR: menyatakan masalah dengan kondisi AND atau OR.

## Contoh Kasus – Ember

- Dua ember kapasitas 4 galon (A) dan 3 galon (B). Target: ember A berisi 2 galon.
- Representasi: (x,y) → x jumlah air di ember A, y jumlah air di ember 
- Initial state: (0,0). Goal state: (2,n).
- Aturan: isi ember, buang air, tuang antar ember.
- Penyelesaian: dilakukan dengan pohon pelacakan hingga ditemukan solusi.