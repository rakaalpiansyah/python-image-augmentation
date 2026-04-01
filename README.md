
markdown
# 🤖 Augmentasi Citra Otomatis (Batch Processing)
[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

> Repositori ini berfokus pada otomatisasi augmentasi data citra. Skrip di dalamnya dirancang untuk memproses banyak gambar sekaligus (*batch processing*) menggunakan operasi transformasi geometris.

## ✨ Fitur Utama
- **🔄 Transformasi Geometris:** Implementasi *Resizing*, *Cropping*, *Flipping* (Sumbu X/Y), dan rotasi menggunakan matriks (`cv2.warpAffine`).
- **⚙️ Otomatisasi (Batch Processing):** Menggunakan perulangan (*looping*) untuk mengaplikasikan 4 jenis augmentasi berbeda ke 10 gambar sekaligus.
- **📁 Manajemen File Dinamis:** Skrip secara otomatis mengekstrak nama file, mengubah ekstensi input menjadi format standar (`.jpg`), dan menyimpannya ke dalam direktori *output* khusus.
