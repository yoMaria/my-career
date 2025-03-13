# 📦 Analisis Keterlambatan Pengiriman E-Commerce  

📌 **Deskripsi Proyek**  
Proyek ini bertujuan untuk **menganalisis faktor keterlambatan pengiriman barang dalam e-commerce** menggunakan **Analisis Deskriptif, Prediktif, dan Preskriptif**. Dengan memanfaatkan **Machine Learning (ML)**, model ini mampu mengidentifikasi penyebab utama keterlambatan serta memberikan rekomendasi untuk meningkatkan efisiensi pengiriman.  

---

## 📂 Struktur Proyek  
📁 **shipping_analysis/**  
├── 📄 **shipping_case.ipynb** → Notebook utama untuk preprocessing & modeling  
├── 📊 **dataset.csv** → Data historis pengiriman barang  
├── 📝 **README.md** → Dokumentasi proyek ini  

---

## 🔧 Teknologi yang Digunakan  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Machine Learning** (Logistic Regression, Decision Tree, Random Forest)  
- **Data Visualization** (Matplotlib, Seaborn)  
- **Jupyter Notebook**  

---

## 🔍 Metodologi Analisis  

### **1️⃣ Analisis Deskriptif (Apa yang Terjadi?)**  
- Mengeksplorasi dataset untuk memahami pola keterlambatan.  
- Menghitung **persentase pengiriman yang terlambat** (**59.7% dari total pengiriman**).  
- Mengidentifikasi faktor utama seperti **warehouse block, metode pengiriman, dan kategori produk**.  
- **Hasil utama:**  
  - Warehouse **Block F memiliki jumlah pengiriman tertinggi**, yang berpotensi menyebabkan keterlambatan.  
  - **Pengiriman dengan kapal lebih sering mengalami keterlambatan** dibanding moda transportasi lainnya.  

### **2️⃣ Analisis Prediktif (Apa yang Akan Terjadi?)**  
- Membangun model **Machine Learning** untuk **memprediksi apakah suatu pengiriman akan terlambat**.  
- Model yang digunakan: **Logistic Regression, Decision Tree, dan Random Forest**.  
- **Akurasi model terbaik:** `[Masukkan Akurasi Terbaik]`.  

### **3️⃣ Analisis Preskriptif (Apa yang Harus Dilakukan?)**  
- Memberikan rekomendasi berbasis data untuk meningkatkan efisiensi pengiriman.  
- **Rekomendasi utama:**  
  - Mengoptimalkan kapasitas warehouse **Block F** untuk mengurangi beban pengiriman.  
  - Menggunakan metode pengiriman yang lebih cepat untuk produk dengan tingkat kepentingan tinggi.  
  - Meningkatkan sistem prediksi keterlambatan untuk perencanaan logistik yang lebih baik.  

---

## 📈 Hasil & Insight  
- **Model terbaik berhasil memprediksi keterlambatan dengan akurasi `[XX%]`.**  
- **59.7% pengiriman mengalami keterlambatan, dengan faktor utama berasal dari warehouse dan metode pengiriman.**  
- **Rekomendasi yang diberikan dapat membantu meningkatkan efisiensi dan mengurangi keterlambatan pengiriman.**  

---

## 📌 Cara Menjalankan Proyek  
1️⃣ Clone repositori ini:  
   ```bash
   git clone https://github.com/username/my-career.git
