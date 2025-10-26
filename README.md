# Proyek Deteksi Objek menggunakan YOLO: Eksperimen pada Data Gambar
## SIP 107 Rancang Bangun Sistem Berbasis AI

Sebagai  bentuk pemenuhan tugas kelompok untuk mata kuliah **SIP 107: Rancang Bangun Sistem Berbasis AI,** kami membuat, melatih, dan menguji sebuah model deep learning yang dapat mendeteksi dan mengklasifikasikan tiga jenis buah: jeruk, pisang, dan apel.


## Anggota Kelompok
* Runi Dwi Jiasta (202304560001)
* Teresa Kaena Dharmanyoto (202304560014)
* Caroline Evarista Den Lau (202304560027)
* Andrew Riza Rafhael (202304560030)

## Dataset
Dataset yang digunakan adalah "Fruit Images for Object Detection" dari [Kaggle](https://www.kaggle.com/datasets/mbkinaci/fruit-images-for-object-detection), yang di-hosting dan diproses melalui Roboflow.
* **Link Roboflow Project:** [https://app.roboflow.com/kaes/fruit-detection-9aqcd/1](https://app.roboflow.com/kaes/fruit-detection-9aqcd/1)

## Isi Repositori
* `Tugas Kelompok_Fruit Detection.ipynb`: [Notebook Google Colab](https://colab.research.google.com/drive/1ew9ePfMKv3LplhY6TiAKLCQ73RFrM_fx?usp=sharing) yang berisi semua kode untuk *training* dan validasi.
* `Laporan Tugas_Kelompok Fruit Detection.pdf`: Laporan akhir proyek.
* `predict/`: Folder berisi gambar-gambar hasil deteksi (gambar + label box) dari *test set*.
* `best.pt`: File bobot (*weights*) model YOLOv8n yang telah dilatih.
* `yolov8n.pt`: File model YOLOv8 'Nano' *pre-trained* asli dari Ultralytics yang digunakan sebagai dasar *transfer learning*.
