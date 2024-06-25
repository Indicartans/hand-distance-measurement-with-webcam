# hand-distance-measurement-with-webcam

# Pengukuran Jarak Tangan Menggunakan Python

Proyek ini menunjukkan cara mengukur jarak antara dua titik spesifik pada tangan secara real-time menggunakan webcam. Proyek ini memanfaatkan beberapa library Python termasuk OpenCV untuk pemrosesan gambar, HandTrackingModule dari `cvzone` untuk deteksi tangan, NumPy untuk perhitungan numerik, dan Math untuk perhitungan jarak.

## Fitur

- Deteksi tangan secara real-time
- Pengukuran jarak antara dua titik spesifik pada tangan
- Konversi jarak dalam piksel ke satuan dunia nyata (sentimeter)
- Menampilkan jarak yang diukur pada umpan video

## Persyaratan

- Python 3.x
- OpenCV
- cvzone
- NumPy

## Instalasi

1. **Kloning repositori:**
    ```bash
    git clone https://github.com/username/hand-distance-measurement.git
    cd hand-distance-measurement
    ```

2. **Instal library yang diperlukan:**
    ```bash
    pip install opencv-python cvzone numpy
    ```

## Penggunaan

Jalankan skrip `hand_distance_measurement.py` untuk mulai mengukur jarak tangan secara real-time.

```bash
python hand_distance_measurement.py
