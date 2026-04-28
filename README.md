# 🚲 Bike Sharing Dashboard

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis pola penyewaan sepeda berdasarkan musim, kondisi cuaca, jenis hari, dan jam penggunaan.

Dashboard ini dibuat menggunakan **Streamlit** untuk memvisualisasikan data Bike Sharing pada periode **2011–2012** agar lebih mudah dipahami.

---

## 📊 Pertanyaan Bisnis

1. Pada periode 2011–2012, musim dan kondisi cuaca mana yang menghasilkan rata-rata jumlah penyewaan sepeda harian tertinggi dan terendah, sehingga perusahaan dapat menentukan waktu terbaik untuk promosi dan pengelolaan armada?
2. Pada periode 2011–2012, pada jam berapa permintaan penyewaan sepeda paling tinggi pada hari kerja dan hari non-kerja, sehingga perusahaan dapat mengatur distribusi sepeda berdasarkan pola waktu penggunaan?

---

## 📁 Struktur Folder
submission/
├── dashboard/
│ ├── main_data.csv
│ └── dashboard.py
├── data/
│ ├── day.csv
│ └── hour.csv
├── notebook.ipynb
├── README.md
├── requirements.txt
└── url.txt


---

## ⚙️ Setup Environment

### 1. Clone Repository

```bash
git clone <repository-url>
cd submission
```

### 2. Virtual Environment

```bash
python -m venv venv
```

```bash
#Windows
venv\Scripts\activate
```

```bash
#Mac / Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Menjalankan Dashboard

```bash
streamlit run dashboard/dashboard.py
```

### 5. Fitur Dashboard

- Ringkasan metrik
- Analisis berdasarkan musim
- Analisis berdasarkan cuaca
- Pola per jam
- Hari kerja vs non-kerja
- Kategori demand
- Filter interaktif

### 6. Insight

- Musim Fall memiliki rata-rata jumlah penyewaan sepeda harian tertinggi.
- Kondisi cuaca cerah menghasilkan jumlah penyewaan tertinggi dibandingkan kondisi cuaca lainnya.
- Pada hari kerja, permintaan tertinggi terjadi pada jam berangkat dan pulang kerja, yaitu sekitar pukul 08.00 serta 17.00–18.00.
- Pada hari non-kerja, permintaan cenderung meningkat pada siang hingga sore hari.

### 7. Rekomendasi

- Menambah ketersediaan sepeda pada musim Fall karena permintaan cenderung lebih tinggi.
- Mengoptimalkan distribusi sepeda saat cuaca cerah.
- Menempatkan lebih banyak sepeda pada jam sibuk hari kerja, terutama pukul 08.00 dan 17.00–18.00.
- Pada hari non-kerja, distribusi sepeda dapat difokuskan pada siang hingga sore hari.

### 8. Tools

- Python
- Pandas
- Matplotlib
- Seaborn
- Streamlit

### 9. Requirements

- pandas
- matplotlib
- seaborn
- streamlit
