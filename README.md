# Operasi Dasar pada Sinyal dan Citra

## Identitas Mahasiswa

Dinda Aliya Nabilah
452024618082
TI/5 C1

## Deskripsi Project

Project ini merupakan implementasi operasi dasar pada sinyal 1D dan citra 2D menggunakan Python pada Google Colab. Eksperimen meliputi operasi penjumlahan, penggeseran (shift), amplifikasi, serta pengujian sistem linier menggunakan konsep homogenitas dan additivitas.

## Library yang Digunakan

* NumPy
* Matplotlib
* OpenCV (cv2)

## Cara Menjalankan Notebook

1. Buka file notebook (.ipynb) menggunakan Google Colab atau Jupyter Notebook.
2. Upload citra yang akan digunakan pada bagian operasi citra.
3. Jalankan seluruh cell secara berurutan.
4. Amati hasil grafik, citra, dan pengujian sistem linier yang dihasilkan.

## Struktur Folder Project

```
project/
│
├── notebook/
│   └── operasi_sinyal_citra.ipynb
│
├── images/
│   ├── citra1.jpg
│   └── citra2.jpg
│
├── report/
│   └── laporan.pdf
│
└── README.md
```

## Ringkasan Hasil Eksperimen

* Operasi penjumlahan meningkatkan amplitudo sinyal dan brightness citra.
* Operasi penggeseran mengubah posisi sinyal maupun objek pada citra tanpa mengubah bentuk dasarnya.
* Operasi amplifikasi memengaruhi amplitudo sinyal dan tingkat kecerahan citra.
* Sistem T(x)=2x memenuhi homogenitas dan additivitas sehingga termasuk sistem linier.
* Sistem T(x)=x² tidak memenuhi homogenitas dan additivitas sehingga termasuk sistem nonlinier.

## Kesimpulan Singkat

Operasi dasar seperti penjumlahan, penggeseran, dan amplifikasi merupakan konsep penting dalam Pengolahan Sinyal Digital. Selain itu, pengujian homogenitas dan additivitas menunjukkan bahwa suatu sistem harus memenuhi kedua sifat tersebut agar dapat dikategorikan sebagai sistem linier.
