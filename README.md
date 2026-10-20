# Implementasi List Komponen via RecyclerView

Penugasan Modul 1 - Praktikum Aplikasi Mobile (PAM)

## Ringkasan Proyek
Aplikasi ini dirancang untuk mendemonstrasikan efisiensi komponen `RecyclerView` dalam menampilkan sekumpulan data berbentuk daftar berurutan pada platform Android. Sistem generate data dummy sebanyak 20 entri secara otomatis dan menampilkannya secara vertikal memakai `CustomAdapter`.

## Fitur Aplikasi
Penyajian Data Dinamis: Menghasilkan dan menampilkan 20 elemen data bertipe teks ("Item 1" - "Item 20").
Layout Berbasis CardView: Pengaplikasian `CardView` sebagai wadah visual tiap elemen item.
Penerapan Adapter & ViewHolder: Pemisahan logika logika data dan rendering UI menggunakan `CustomAdapter`.
Pencatatan Log System: Menuliskan jumlah data terproses ke Logcat dengan tag `test string`.

## Spesifikasi & Library
*Bahasa: Kotlin
*SDK Minimum: API level 27 (Android 8.1 Oreo)
*Komponen UI: `RecyclerView`, `CardView`, `ConstraintLayout`
*Build Tool: Gradle (Kotlin DSL)[cite: 1]

## Arsitektur Berkas
```text
.
├── app/
│   └── src/
│       └── main/
│           ├── java/lat/pam/recyclerviewsampel/
│           │   ├── CustomAdapter.kt
│           │   ├── ItemsViewModel.kt
│           │   └── MainActivity.kt
│           └── res/
│               └── layout/
│                   ├── activity_main.xml
│                   └── card_view_design.xml
