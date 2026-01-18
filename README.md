# EcoEarth

**EcoEarth** adalah aplikasi cerdas berbasis AI untuk mendeteksi dan mengklasifikasikan jenis sampah (Organik, Anorganik, Non-Trash) secara realtime menggunakan kamera. Proyek ini bertujuan untuk memudahkan proses pemilahan sampah demi lingkungan yang lebih bersih.

## Fitur Utama

- **Deteksi Realtime**: Menggunakan kamera untuk mengenali sampah secara langsung.
- **Klasifikasi Cerdas**: Membedakan sampah menjadi beberapa kategori (misal: Organik, Anorganik, Non-Human).
- **Dashboard Interaktif**: Menampilkan hasil deteksi melalui antarmuka web yang user-friendly.

## Teknologi yang Digunakan

- **Python**: Bahasa pemrograman utama.
- **YOLOv8**: Model Deep Learning untuk deteksi objek (sampah).
- **Flask**: Web framework untuk menjalankan aplikasi.
- **OpenCV**: Library untuk pemrosesan citra/video.

## Struktur Folder

- `EcoEarth.ipynb` & `SmarthBin.ipynb`: Notebook Jupyter untuk eksperimen dan pelatihan model.
- `best.pt` & `yolov8n.pt`: File model AI yang sudah dilatih.
- `templates/` & `static/`: File antarmuka website (HTML/CSS).
- `dataset/`: Data gambar untuk melatih model.

## Cara Instalasi & Penggunaan

1.  **Clone Repository**
    ```bash
    git clone https://github.com/fifinurfadillah/EcoEarth.git
    cd EcoEarth
    ```

2.  **Install Dependencies**
    Pastikan Python sudah terinstall, lalu install library yang dibutuhkan (contoh):
    ```bash
    pip install ultralytics flask opencv-python
    ```

3.  **Jalankan Aplikasi**
    Buka terminal dan jalankan notebook utama untuk melatih atau menjalankan deteksi:
    ```bash
    # Buka Jupyter Notebook
    jupyter notebook EcoEarth.ipynb
    ```
    Atau jika sudah dikonversi ke script python:
    ```bash
    python app.py
    ```

