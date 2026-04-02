<div align="center">

# LAPORAN PRAKTIKUM  
## APLIKASI BERBASIS PLATFORM  

### TUGAS COTS-1  
### WEB MANAJEMEN PRODUK KOMPUTER  
### "SYARIAH KOMPUTER"

<br>

<img src="https://github.com/user-attachments/assets/22ae9b17-5e73-48a6-b5dd-281e6c70613e" width="300"/>

<br><br>

### Disusun Oleh:
**Arvan Murbiyanto**  
**2311102074**  
**S1 IF-11-04**

<br>

### Dosen Pengampu:
**Cahyo Prihantoro, S.Kom., M.Eng.**

<br>

### Asisten Praktikum:
**Apri Pandu Wicaksono**  
**Rangga Pradarrell Fathi**

<br><br>

### LABORATORIUM HIGH PERFORMANCE  
FAKULTAS INFORMATIKA  
UNIVERSITAS TELKOM PURWOKERTO  
2026

</div>

---

## 📖 Deskripsi Aplikasi

Aplikasi **Syariah Komputer** merupakan sistem informasi berbasis web untuk mengelola data part komputer. Aplikasi ini mengimplementasikan konsep **CRUD (Create, Read, Update, Delete)** dengan arsitektur **client-server** menggunakan **REST API**.

- **Frontend:** HTML, Bootstrap, jQuery  
- **Backend:** Node.js + Express.js  
- **Data:** In-memory (JSON)

---

## 📚 1. Dasar Teori

- **CRUD** → Operasi dasar pengelolaan data  
- **Node.js** → Runtime JavaScript backend (non-blocking)  
- **Express.js** → Framework REST API  
- **Bootstrap** → UI responsif  
- **jQuery** → Manipulasi DOM & AJAX  
- **DataTables** → Tabel interaktif  
- **JSON** → Format pertukaran data  

---

## 🧩 2. Fitur Aplikasi

- Menampilkan data part  
- Menambahkan data  
- Edit data  
- Hapus data  
- Tabel interaktif  
- Tanpa database (JSON)

---

## 📁 3. Struktur Project

```bash
tugas-cots-2311102180/
├── server.js
├── package.json
├── public/
│   ├── index.html
│   ├── tambah.html
│   ├── edit.html
│   ├── script.js
└── assets/
    ├── beranda.png
    ├── edit_part.png
    ├── tambah_part.png
    ├── hapus_part.png
