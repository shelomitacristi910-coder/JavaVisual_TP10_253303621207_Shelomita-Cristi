# Character Manager

Buka folder `C:\CharacterManager3` sebagai workspace VS Code agar `src` dikenali sebagai source root dan package `com.unpri.charactermanager` dapat di-resolve.

## TP10 — Theming, Properti Komponen & Analisis MVC

Tema warna, font, dan border antarmuka didefinisikan di `AppTheme` pada package `view`. Model `Character` menyimpan data karakter, bukan aturan bagaimana data itu ditampilkan. Dengan demikian, perubahan tema tidak mengubah logika model dan tampilan lain dapat menyajikan karakter yang sama dengan gaya berbeda. Pemetaan role ke warna juga terpusat sehingga konsisten dan mudah dirawat.

### Properti tambahan

- **Tooltip detail HP/ATK/Mana:** detail statistik tersedia saat kartu diarahkan mouse tanpa membuat daftar terlihat sesak.
- **Border kartu mengikuti role:** garis tepi menggunakan warna role agar kategorinya tetap mudah dikenali dan konsisten dengan warna latar kartu.

### Screenshot

Tambahkan hasil tangkapan layar aplikasi v0.3 dan v0.4 di `docs/screenshots/`, lalu sesuaikan nama berkas di bawah. Pastikan gambar v0.3 benar-benar diambil dari versi sebelum perubahan tema, dan gambar v0.4 dari aplikasi yang sudah berjalan.

| Sebelum — v0.3 | Sesudah — v0.4 |
|---|---|
| ![Character Manager v0.3](docs/screenshots/character-manager-v03.png) | ![Character Manager v0.4](docs/screenshots/character-manager-v04.png) |

### Analisis Bagian D

Tulis analisis minimal 500 kata dengan kata-kata sendiri di Google Docs. Bahas JavaBeans getter/setter, `setBackground` dan `setOpaque`, `setSize`/`setPreferredSize`/`pack`, alasan menghindari null layout dan `setBounds`, pemisahan Model-View, serta logical fonts dan `deriveFont`. Sebelum submit, ganti placeholder ini dengan tautan Google Docs Anda: **[Tautan Google Docs TP10 — tambahkan di sini]**.
