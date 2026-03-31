# 🎲 Dice Roller App

> Aplikasi Android berbasis **Jetpack Compose** yang mensimulasikan lemparan dadu dengan fitur interaktif berupa perubahan warna latar belakang dinamis.

## 👩‍🎓 Identitas

| Field | Detail |
|-------|--------|
| **Nama** | Amanda Illona Farrel |
| **NRP** | 5025221056 |
| **Mata Kuliah** | Pemrograman Perangkat Bergerak (C) |

## ✨ Fitur Aplikasi

- 🎲 **Random Dice Logic** -> Mekanisme pengacakan angka 1–6 menggunakan fungsi `.random()` yang sinkron dengan UI.
- 🌈 **Dynamic Background** -> Seluruh layar akan berubah warna secara otomatis menyesuaikan angka dadu yang keluar.
- ⏳ **Smooth Transitions** -> Implementasi `animateColorAsState` untuk memberikan efek transisi warna yang halus (600ms) agar tidak kaku.
- 🏆 **Jackpot Feedback** -> Warna kuning cerah khusus diberikan saat pengguna mendapatkan angka **6**.
- 🔘 **Custom UI Contrast** -> Pengaturan warna tombol menjadi *Dark Gray* untuk memastikan aksesibilitas dan kontras tetap terjaga di atas warna latar apa pun.

## 🛠️ Tech Stack

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)

## 💡 Yang Dipelajari

- Mengelola **State** menggunakan `remember` dan `mutableStateOf` untuk menangani perubahan data secara real-time.
- Menggunakan **When Expression** secara efektif untuk memetakan logika bisnis ke *Image Resource* dan *Color Resource*.
- Menerapkan **Animation API** pada Compose (`animateColorAsState`) untuk menciptakan pengalaman pengguna yang lebih premium.
- Mengatur tata letak deklaratif menggunakan `Column`, `Spacer`, dan `Modifier` untuk responsivitas *layout*.
- Memahami konsep **Conditional Styling** dalam komponen UI Android.

---

<p align="center">
  ✨ Dibuat untuk memenuhi tugas <strong>Pemrograman Perangkat Bergerak</strong> ✨
</p>
