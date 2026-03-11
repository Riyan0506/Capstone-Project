# Capstone-Project

# ANALISIS SENTIMEN ULASAN SHOPEE DENGAN MACHINE LEARNING DAN AI SUPPOR

Proyek ini bertujuan untuk menganalisis sentimen ulasan pengguna pada aplikasi **Shopee** menggunakan pendekatan machine learning.  
Analisis dilakukan untuk mengetahui persepsi pengguna terhadap layanan Shopee, apakah cenderung **positif** atau **negatif**.

---

## 📂 Dataset
Dataset berisi ulasan pengguna aplikasi Shopee.  
Link dataset: [Klik di sini](https://www.kaggle.com/datasets/herafajrin/shopee-review-indonesian)    

---

## ⚙️ Tools & Library
- Python 3 (Google Colab)
- Pandas
- Numpy
- Scikit-learn
- Matplotlib & Seaborn
- NLTK / Sastrawi (untuk preprocessing teks)

---

## 🔄 Proses Analisis
1. **Data Collection** → Mengambil dataset ulasan pengguna.  
2. **Preprocessing** → Case folding, stopword removal, stemming, tokenizing.  
3. **Feature Extraction** → TF-IDF Vectorizer.  
4. **Model Training** → Algoritma machine learning (contoh: Naive Bayes / SVM).  
5. **Evaluation** → Menggunakan Confusion Matrix, Accuracy, Precision, Recall, dan F1-Score.  

---

## 📊 Hasil & Temuan
- Model dapat memprediksi sentimen ulasan dengan tingkat akurasi yang baik.  
- Berdasarkan confusion matrix:  
  - **True Negatif (148)**: ulasan negatif yang terprediksi negatif.  
  - **False Positif (61)**: ulasan negatif yang terprediksi positif.  
  - **False Negatif (36)**: ulasan positif yang terprediksi negatif.  
  - **True Positif (343)**: ulasan positif yang terprediksi positif.  

📈 Visualisasi hasil terdapat pada notebook Colab.  

---

## 📌 Kesimpulan & Rekomendasi
- Mayoritas ulasan pengguna Shopee bersifat **positif**.  
- Masih terdapat ulasan negatif yang perlu diperhatikan, terutama terkait layanan tertentu.  
- Rekomendasi: meningkatkan layanan pengiriman dan pengalaman belanja agar kepuasan pengguna tetap tinggi.  
 

---

## 🚀 Notebook
Link Google Colab: [Klik di sini](https://colab.research.google.com/drive/1wXOlvh-xlRhtuEcJU_RRxSQPkzXG5ZM9?usp=sharing)   

---

## 👨‍💻 Author
- Nama: **Muhammad Riyan Maulana**  
- Universitas: Universitas Gunadarma  
