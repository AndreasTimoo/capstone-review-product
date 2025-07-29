# Capstone Project: Analisis Review Produk E-commerce

## 📌 Overview
Proyek ini bertujuan untuk menganalisis review produk dari marketplace Indonesia menggunakan bantuan AI (LLM).  
Fokus utama analisis:
- Klasifikasi sentimen berdasarkan teks review pelanggan.
- Ringkasan otomatis dari review panjang.
- Visualisasi insight dari data lokasi, rating, dan penjualan.

## 📊 Dataset
- Nama file: `review_dataset.csv`
- Jumlah data: 20+ produk elektronik
- Kolom penting: `Customer Review`, `Sentiment`, `Emotion`, `Location`, `Number Sold`, `Overall Rating`

Dataset ini berasal dari review marketplace Indonesia (data dummy). Disimpan di folder `/data`.

## ⚙️ Tools & Teknologi
- **Python (Google Colab)**
- **HuggingFace Transformers**
  - Sentiment analysis: `distilbert-base-uncased-finetuned-sst-2-english`
  - Summarization: `facebook/bart-large-cnn`
- Visualisasi: `matplotlib`, `seaborn`

## 📈 Insight & Findings
- Mayoritas review bersentimen positif (lebih dari 90%)
- Produk dengan rating tinggi dan harga menengah lebih banyak terjual
- Lokasi distribusi produk terbanyak: Jakarta dan sekitarnya
- Model AI dapat memberikan ringkasan singkat dari review panjang

## 🎯 Conclusion & Recommendations
- Penjual disarankan mempertahankan kualitas produk dan layanan untuk menjaga sentimen positif.
- Area Jakarta adalah lokasi strategis untuk distribusi karena dominasi transaksi.
- Bisa dikembangkan ke prediksi tren penjualan berbasis sentimen.

## 🤖 AI Model Support
- **Sentiment Classification**: menggunakan LLM (`distilbert`) untuk validasi label sentimen
- **Text Summarization**: menggunakan `facebook/bart-large-cnn` untuk merangkum review panjang

## 🔗 Links
- [Google Colab Notebook](https://colab.research.google.com/drive/your-colab-link-here)
- [Dataset Folder](./data/review_dataset.csv)
- [Presentation Slides](./slides/presentasi_capstone.pdf)

---


