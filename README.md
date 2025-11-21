# Kalkulator Interaktif JavaScript Tailwind

Aplikasi kalkulator web interaktif yang dibangun dengan JavaScript dan Tailwind CSS. Dilengkapi dengan fungsi memori, riwayat perhitungan, dukungan keyboard, dan desain responsif dengan tema gelap yang elegan.

## Fitur Utama

- **Operasi Aritmatika Dasar**: Penjumlahan, pengurangan, perkalian, dan pembagian
- **Fungsi Lanjutan**: Kuadrat (x²), akar kuadrat (√), resiprokal (1/x), persentase (%)
- **Fungsi Memori**: 
  - M+ (Memory Add) - Menambahkan nilai ke memori
  - M- (Memory Subtract) - Mengurangi nilai dari memori
  - MR (Memory Recall) - Memanggil nilai dari memori
  - MC (Memory Clear) - Menghapus memori
- **Riwayat Perhitungan**: Menyimpan 5 perhitungan terakhir dengan kemampuan klik untuk menggunakan kembali hasil
- **Dukungan Keyboard**: Input lengkap melalui keyboard
- **Desain Responsif**: Tampilan optimal di desktop dan mobile
- **Tema Elegan**: Desain monokrom hitam dengan aksen minimal

## Teknologi yang Digunakan

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla JS)
- Google Fonts (Inter)

## Cara Menggunakan

### Online
Buka file `kalkulator-interaktif.html` di browser web modern.

### Lokal
1. Clone repository ini
```bash
git clone https://github.com/RiskiJayaPutra/kalkulator-interaktif-javascript-tailwind.git
```

2. Buka file `kalkulator-interaktif.html` di browser

## Keyboard Shortcuts

- **Angka 0-9**: Input angka
- **Operator (+, -, *, /)**: Operasi matematika
- **Enter atau =**: Hitung hasil
- **Escape**: Clear semua (C)
- **Backspace**: Hapus digit terakhir
- **.** atau **,**: Titik desimal
- **%**: Persentase

## Fungsi Memory

### M+ (Memory Add)
Menambahkan angka yang ditampilkan di layar ke dalam memori.

Contoh: Layar menampilkan 50, tekan M+, memori sekarang berisi 50.

### M- (Memory Subtract)
Mengurangi angka yang ditampilkan di layar dari memori.

Contoh: Memori berisi 100, layar menampilkan 30, tekan M-, memori menjadi 70.

### MR (Memory Recall)
Memanggil dan menampilkan nilai yang tersimpan di memori ke layar.

Contoh: Memori berisi 150, tekan MR, layar akan menampilkan 150.

### MC (Memory Clear)
Menghapus atau mereset memori menjadi 0. Indikator "M" akan hilang.

## Screenshot

### Tampilan Utama
Kalkulator dengan desain elegan hitam dan layar putih yang kontras.

### Panel History
Menyimpan riwayat perhitungan yang dapat diklik untuk digunakan kembali.

## Struktur Kode

### HTML Structure
- Display Section: Menampilkan angka dan operasi
- Memory Display: Menampilkan nilai yang tersimpan di memori
- Calculator Buttons: Grid 5 kolom untuk tombol-tombol
- History Panel: Sidebar untuk riwayat perhitungan

### JavaScript Functions
- `appendNumber()`: Input angka
- `chooseOperation()`: Memilih operasi matematika
- `compute()`: Menghitung hasil
- `memoryAdd()`, `memorySubtract()`, `memoryRecall()`, `memoryClear()`: Fungsi memori
- `addToHistory()`: Menambahkan ke riwayat
- `updateDisplay()`: Update tampilan

### CSS Styling
- Glass morphism effect pada panel kalkulator
- Gradient background hitam-abu
- Animasi hover dan ripple effect pada button
- Responsive grid layout

## Browser Support

- Chrome (Recommended)
- Firefox
- Safari
- Edge
- Opera

## Lisensi

MIT License

## Kontributor

Riski Jaya Putra

## Kontak

GitHub: [@RiskiJayaPutra](https://github.com/RiskiJayaPutra)

---

Dibuat dengan JavaScript dan Tailwind CSS
