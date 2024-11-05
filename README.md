# 📜 Dataset Putusan Pengadilan: Kasus Narkotika & Psikotropika - PN Surabaya 2024
Selamat datang! Dataset ini membawa Anda menyelami dunia hukum di Indonesia, khususnya pada kasus-kasus Narkotika dan Psikotropika dari Pengadilan Negeri Surabaya tahun 2024. Berisi 50 putusan, dataset ini diambil dari Direktori Putusan Mahkamah Agung RI, sumber terpercaya dalam pendokumentasian hukum di Indonesia.

## Tentang Dataset
Dataset ini berfokus pada putusan-putusan dalam kategori Pidana Khusus dengan klasifikasi Narkotika dan Psikotropika. Dalam setiap entri, Anda akan menemukan informasi penting terkait hasil putusan serta barang bukti yang relevan.
### Rincian Dataset
- Kategori: Pidana Khusus
- Klasifikasi Kasus: Narkotika dan Psikotropika
- Lokasi: Pengadilan Negeri Surabaya
- Tahun: 2024
- Jumlah Putusan: 50 kasus
- Status: Tidak termasuk putusan dengan status berkekuatan hukum tetap
### Fitur dalam Dataset
| Fitur               | Deskripsi                                                                                         |
|---------------------|---------------------------------------------------------------------------------------------------|
| `No_Putusan`       | Nomor putusan dari setiap kasus sebagai identitas unik                                            |
| `Lembaga_Peradilan`| Nama lembaga yang menangani kasus, yaitu Pengadilan Negeri Surabaya                                |
| `Barang_Bukti`     | Daftar barang bukti yang digunakan dalam proses persidangan, seperti narkotika, alat bukti, dll.   |
| `Amar_Putusan`     | Keputusan akhir dari hakim yang mencakup hukuman atau tindakan yang harus dijalani terdakwa        |

## Kegunaan Dataset
Dataset ini sangat berpotensi untuk berbagai jenis analisis hukum dan sosial, antara lain:
- Analisis Tren: Memahami pola putusan yang umum dalam kasus narkotika di Surabaya.
- Studi Implementasi Hukum: Menganalisis bagaimana Pengadilan Negeri Surabaya menerapkan peraturan terkait narkotika dan psikotropika.
- Model Prediktif: Mengembangkan model untuk memprediksi hasil putusan berdasarkan bukti yang disajikan di pengadilan.
- Penelitian Sosial: Memahami dampak barang bukti tertentu terhadap amar putusan atau hukuman yang dijatuhkan.

## Cara menggunakan
Dataset tersedia dalam format .csv dan dapat diakses langsung menggunakan Python atau alat analisis data lainnya:
```python
import pandas as pd

# Memuat dataset dari file Excel
data = pd.read_excel("Overview.xlsx")

# Menampilkan beberapa baris data
data.head()
```

## 📌 Lisensi & Batasan
Dataset ini diperuntukkan untuk kepentingan pendidikan dan penelitian. Mohon perhatikan bahwa informasi dalam dataset ini disesuaikan agar tetap menjaga kerahasiaan data dan privasi sesuai dengan peraturan yang berlaku di Indonesia.

Terima kasih telah berkunjung, dan semoga dataset ini bermanfaat bagi riset dan pemahaman Anda tentang hukum di Indonesia! 👩‍⚖️👨‍⚖️
