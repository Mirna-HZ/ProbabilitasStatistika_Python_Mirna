# Tugas Eksplorasi dan Implementasi Python: Probabilitas dan Distribusi Probabilitas

Mata kuliah Probabilitas dan Statistika, Program Studi Teknik Informatika, Politeknik Caltex Riau.  
Disusun oleh Mirna (3 TI F).

Repositori ini berisi kode Python untuk menyelesaikan permasalahan probabilitas dan distribusi probabilitas dengan contoh kasus bidang Teknik Informatika. Setiap permasalahan dihitung secara manual, dihitung dengan Python, lalu diperiksa dengan simulasi apabila memungkinkan.

## Notebook

| Notebook | Isi | Buka di Colab |
|---|---|---|
| [01_Permasalahan_Probabilitas.ipynb](01_Permasalahan_Probabilitas.ipynb) | 12 permasalahan probabilitas | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mirna-HZ/ProbabilitasStatistika_Python_Mirna/blob/main/Tugas_Eksplorasi_Python/01_Permasalahan_Probabilitas.ipynb) |
| [02_Distribusi_Probabilitas.ipynb](02_Distribusi_Probabilitas.ipynb) | 15 permasalahan distribusi probabilitas | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mirna-HZ/ProbabilitasStatistika_Python_Mirna/blob/main/Tugas_Eksplorasi_Python/02_Distribusi_Probabilitas.ipynb) |

## Daftar Permasalahan

**Probabilitas**

1. Ruang Sampel dan Probabilitas Klasik: String 4 Bit Acak
2. Probabilitas Simbolik dan Bersyarat dengan sympy.stats: Dua Dadu 8 Sisi
3. Permutasi dan Kombinasi: Kode Akses dan Tim Hackathon
4. Aturan Komplemen dan Inklusi-Eksklusi: Kekuatan Password Acak
5. Probabilitas Bersyarat dari Data Log Server
6. Kejadian Saling Bebas: Keandalan Sistem Seri dan Paralel
7. Teorema Probabilitas Total dan Teorema Bayes: Crash Aplikasi per Versi Android
8. Teorema Bayes Bertahap: Deteksi Akun Bot di Media Sosial
9. Teorema Bayes dari Sisi Penolakan: Face Unlock pada Smartphone
10. Simulasi Percobaan Acak: Masalah Monty Hall
11. Hukum Bilangan Besar: Pembagian Request oleh Load Balancer
12. Probabilitas Empiris dari Data Rating Aplikasi

**Distribusi Probabilitas**

1. Distribusi Bernoulli: Keberhasilan Build CI/CD
2. Distribusi Binomial: Email Notifikasi Masuk Folder Spam
3. Distribusi Poisson: Tiket Helpdesk IT per Jam
4. Aproksimasi Poisson terhadap Binomial: Bug pada Kode Program
5. Distribusi Geometrik: Pengujian Acak hingga Bug Pertama Ditemukan
6. Distribusi Hipergeometrik: Quality Control SSD dari Pemasok
7. Distribusi Uniform Kontinu: Waktu Respons Server
8. Distribusi Normal: Suhu CPU saat Beban Penuh
9. Aproksimasi Normal terhadap Binomial: Ulasan Aplikasi
10. Distribusi Eksponensial: Lama Sesi Pengguna Aplikasi
11. Hubungan Distribusi Eksponensial dan Poisson: Simulasi Pesan Masuk Chat Server
12. Variabel Acak Kontinu: Waktu Pemrosesan Request dengan Fungsi Kepadatan
13. Distribusi Seragam Diskrit: Digit Kode OTP
14. Distribusi Binomial Negatif: Unduhan Berhasil ke-3 pada Web Crawler
15. Ringkasan Nilai Harapan dan Varians Seluruh Distribusi

## Library yang Digunakan

- Bawaan Python: `math`, `fractions`, `itertools`, `collections`, `random`, `statistics`
- Pihak ketiga: `numpy`, `pandas`, `scipy` (`scipy.stats`, `scipy.integrate`), `sympy`, `matplotlib`, `seaborn`

## Cara Menjalankan

**Google Colab:** klik tombol *Open in Colab* di atas, lalu pilih **Runtime > Run all**. Semua library sudah tersedia di Colab.

**Jupyter Notebook lokal:**

```bash
pip install -r requirements.txt
jupyter notebook
```

Seed acak ditetapkan di awal setiap notebook sehingga hasil simulasi dapat diulang.
