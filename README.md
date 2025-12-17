# UAS Struktur Data: Aplikasi Pencarian Game (Hash Table) 

Repository ini berisi codingan untuk **Ujian Akhir Semester (UAS)** mata kuliah Pengantar Algoritma dan Struktur Data.

Intinya, ini adalah program Python buat **mencari dan mengelola data penjualan game** (dari Kaggle). Bedanya, di sini kita nggak pakai `dictionary` biasa, tapi bikin struktur data **Hash Table** sendiri secara manual.

---

##  Apa Saja Fiturnya?

1.  **Cari Game Cepat**: Bisa cari game berdasarkan **Judul**, **Genre**, atau **Publisher** (ketik sebagian kata juga bisa ketemu).
2.  **Top 10 Terlaris**: Bisa langsung lihat urutan 10 game dengan penjualan tertinggi di dunia.
3.  **Tambah & Hapus Data**: Bisa input data game baru atau menghapus data yang sudah ada.
4.  **Manual Hash Table**: Menerapkan rumus *hashing* dan teknik *Chaining* (Linked List) buat menangani data yang "tabrakan".
5.  **Data Banyak**: Bisa baca ribuan data dari file Excel/CSV.

---

## 📂 Bahan-bahan

* **Bahasa**: Python 3
* **File Data**: `VideoGames_Sales.csv` (Isinya data penjualan game global).
* **Codingan Utama**: `main.py`

---

## 🚀 Cara Menjalankan

Kamu bisa jalankan program ini pakai software favoritmu (VS Code, PyCharm, dll).

### Cara 1: Paling Gampang (Pakai VS Code) ✨
1.  **Download** kodingan ini (klik tombol hijau **Code** > **Download ZIP**), lalu ekstrak foldernya.
2.  Buka aplikasi **Visual Studio Code**.
3.  Pilih menu **File** > **Open Folder...** lalu pilih folder hasil ekstrak tadi.
4.  Buka file `main.py`.
5.  Klik tombol **Play ▶️** di pojok kanan atas.
    *(Pastikan extension Python di VS Code sudah terinstall ya!)*

### Cara 2: Lewat Terminal / CMD 💻
Buat yang suka pakai command line:
1.  Clone repo ini:
    ```bash
    git clone [https://github.com/AdzamNet/Implementasi-Struktur-Data-Hash-Table-Utuk-Menangani-Data-penjualan-Game-global.bal.git](https://github.com/AdzamNet/Implementasi-Struktur-Data-Hash-Table-Utuk-Menangani-Data-penjualan-Game-global.bal.git)
    ```
2.  Masuk ke foldernya:
    ```bash
    cd Implementasi-Struktur-Data-Hash-Table-Utuk-Menangani-Data-penjualan-Game-global.bal
    ```
3.  Jalankan:
    ```bash
    python main.py
    ```

---

**Dibuat oleh:** Adzam
*Semoga bermanfaat!*
