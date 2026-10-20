Studi Kasus Monitoring Deforestasi dengan Machine Learning
Ringkasan
Notebook pembelajaran berdasarkan seminar Dr. Bart Slachter tentang penggunaan citra satelit optik/radar dan AI untuk klasifikasi penyebab langsung alert deforestasi. Proyek ini memakai fitur tabular sintetis untuk demonstrasi baseline Random Forest, bukan citra Sentinel asli atau replikasi CNN pembicara.
Cara menjalankan
1. Buka https://colab.research.google.com/
2. Pilih File → Upload notebook, lalu unggah Studi_Kasus_Monitoring_Deforestasi_AI.ipynb.
3. Jalankan sel secara berurutan.
4. Saat diminta, unggah dataset_dummy_alert_deforestasi.csv.
5. Periksa classification report, macro F1, confusion matrix, dan perbandingan baseline.
Isi proyek
- Pemeriksaan kualitas data dan nilai kosong
- Stratified train/test split
- Pipeline imputasi dan Random Forest
- Evaluasi accuracy, macro F1, classification report, dan confusion matrix
- Pembandingan dengan DummyClassifier
- Ekspor hasil prediksi
Batasan penting
Dataset sintetis dengan fitur ilustratif; tidak berasal dari sensor satelit, tidak memetakan lokasi sebenarnya, dan tidak layak untuk keputusan konservasi/penegakan hukum. Evaluasi notebook hanya demonstrasi alur pemodelan. Studi nyata memerlukan citra asli, label terverifikasi, validasi independen, serta pertimbangan kesalahan model.
GitHub
Buat repository studi-kasus-monitoring-deforestasi-ai dan unggah notebook, dataset, serta README ini.
