# DATA MINING ACTION 2025 by Universitas Negeri Surabaya

## Qualification
### Problems
Proyek ini bertujuan untuk mengembangkan model yang dapat mengklasifikasikan makanan Indonesia secara akurat dari citra (gambar). Menggunakan pembelajaran semi-terawasi (semi-supervised learning) dengan arsitektur MLP yang ringan serta SigLIP Vision Transformer untuk ekstraksi fitur, kami berhasil mencapai akurasi sebesar 96%.
- Self-training dengan pseudo-labeling untuk data yang tidak berlabel.
- Mekanisme SE-Attention untuk peningkatan fitur.
- Test-Time Augmentation (TTA) tingkat lanjut.
- Pembobotan kelas (Class weighting) untuk menangani dataset yang tidak seimbang.
- Residual Feed-Forward Networks untuk stabilitas pelatihan.
### Dataset Information
Dataset merupakan data gambar/citra makanan Indonesia yang tidak memiliki label secara eksplisit namun diberikan 15 kelas yang nantinya harus diprediksi.
### Results
- Public LB     : 
- Private LB    :
- Paper

## Finals
### Problems
Babak final dilaksanakan dengan mekanisme yang sama, yaitu kaggle competition. Pada babak final ini peserta diminta untuk melakukan tugas klasifikasi token. Klasifikasi token dilakukan dengan format BIO-Tagging (Beginning, Inside, Outside). Peserta dibebaskan menggunakan model dan teknik apapun, kecuali penggunakan model-model berbasis API Call.
- Menggunakan model XLM-RoBERTa versi Large untuk melakukan klasifikasi token
- Menerapkan metode CRF (Conditional Random Field) yang bertujuan untuk meningkatkan hasil klasifikasi token agar sesuai dengan format BIO
### Dataset Information
Dataset merupakan data teks yang merupakan komentar atau ulasan mengenai kuliner Indonesia. Dataset ini mengandung nama-nama makanan, brand-brand makanan maupun daerah, serta waktu.
### Results
- Public LB     :
- Private LB    :