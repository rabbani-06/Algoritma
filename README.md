# Analisis Algoritma Pengurutan

**Nama:** Muh. Rafi Rabbani  
**NIM:** F55123038  
**Kelas:** B

Proyek ini mengimplementasikan dan menganalisis dua algoritma pengurutan:  
1. Pendekatan Naif (Bubble Sort)  
2. Pendekatan Divide-and-Conquer (Merge Sort)  

## Analisis Best Case

### 1. Bubble Sort (`Pendekatan Naif`)

- **Jumlah Perbandingan:** Hanya perlu `n-1` perbandingan (49 kali untuk array dengan 50 elemen).
- **Jumlah Pertukaran:** Tidak ada pertukaran (`swaps = 0`).

- **Best Case Time Complexity:** `O(n)`
- **Space Complexity:** `O(1)`

### 2. Merge Sort (`conquer.py`)

- **Jumlah Perbandingan:** Tetap `n log(n)` untuk 50 elemen.
- **Jumlah Pertukaran:** Tidak relevan karena hanya terjadi penggabungan.
- 
- **Best Case Time Complexity:** `O(n log(n))`
- **Space Complexity:** `O(n)` (karena membutuhkan array tambahan untuk penggabungan)

