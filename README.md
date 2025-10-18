# Asst1PemroMob_Shopping_Flutter
Project Assesment 1 Pemrograman Mobile membuat aplikasi menggunakan Flutter Fraework dan menerapkan sistem CRUD
# 🛍️ Shopping List App

## 👥 Nama dan NIM Anggota Tim
| Nama | NIM |
|------|------|
| Fadillah Dani Prawoto | 2310130004 |
| Muhamad Hafidz Hazhari | (2310130014) |
| Fathi Fathan fathurrahman Nuryadin | (2310130005) |

---

## 🎯 Tema Aplikasi
Aplikasi **Shopping List** adalah aplikasi Flutter sederhana yang digunakan untuk mencatat daftar belanjaan sehari-hari. Pengguna dapat menambah, mengedit, dan menghapus item belanja dengan mudah.

---

## ⚙️ Deskripsi Singkat Fitur Aplikasi
- ✅ **Tambah Item Belanja:** Pengguna dapat menambahkan item baru melalui form input.  
- 📝 **Daftar Item Belanja:** Semua item yang sudah ditambahkan akan muncul dalam bentuk *List View*.  
- 🗑️ **Hapus Item:** Pengguna bisa menghapus item yang sudah dibeli atau tidak diperlukan.  
- 💾 **Data Disimpan di List:** Data disimpan sementara menggunakan struktur data *List* di Flutter.

---

## 👨‍💻 Pembagian Tugas Antar Anggota
| Nama | Tugas |
|------|-------|
| Fadillah Dani Prawoto | Membuat UI |
| Muhamad Hafidz Hazhari | Membuat konsep CRUD |
| Fathi Fathan fathurrahman Nuryadin | Membuat proses CRUD |

---

## 🖼️ Screenshot Tampilan
**1️⃣ Halaman Daftar Belanja (List View):**  
![List View](screenshots/list_view.png)

**2️⃣ Halaman Form Input:**  
![Form Input](screenshots/form_input.png)

*(Catatan: ganti nama file dan path sesuai screenshot kamu.)*

---

## 🧩 Penjelasan Penggunaan List
Dalam aplikasi ini, data item belanja disimpan menggunakan struktur data **List** di Flutter.

Contoh implementasi:
```dart
List<String> shoppingList = [];
