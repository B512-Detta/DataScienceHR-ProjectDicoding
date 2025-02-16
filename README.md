# Proyek Akhir: Analisis Faktor yang Mempengaruhi Attrition Rate di Jaya Jaya Maju

## Business Understanding

Jaya Jaya Maju merupakan perusahaan multinasional yang telah beroperasi sejak tahun 2000 dengan lebih dari 1000 karyawan yang tersebar di berbagai daerah. Meskipun telah berkembang menjadi perusahaan besar, mereka masih mengalami kesulitan dalam mengelola karyawan. Hal ini terlihat dari tingginya attrition rate (rasio jumlah karyawan yang keluar dibandingkan total karyawan) yang mencapai lebih dari 10%. Jika dibiarkan, kondisi ini dapat berdampak pada stabilitas operasional perusahaan dan peningkatan biaya perekrutan serta pelatihan karyawan baru.

### Permasalahan Bisnis

- Mengidentifikasi faktor-faktor yang mempengaruhi attrition rate di perusahaan.
- Menganalisis hubungan antara variabel tertentu seperti gaji, kepuasan kerja, dan keterlibatan karyawan terhadap keputusan untuk keluar.
- Mengembangkan business dashboard untuk membantu tim HR dalam memonitor faktor-faktor yang mempengaruhi attrition.
  
### Cakupan Proyek

Proyek ini mencakup seluruh tahap dalam data science lifecycle, mulai dari pemahaman bisnis hingga deployment lokal. Fokus utama adalah:
1. Eksplorasi dan analisis data untuk memahami tren attrition.
2. Pengujian hipotesis untuk mengidentifikasi faktor yang berpengaruh.
3. Pembuatan model machine learning untuk memprediksi attrition.
4. Evaluasi model guna memastikan keakuratannya.
5. Pengembangan business dashboard sebagai alat bantu monitoring HR.
6. Dokumentasi lengkap dalam format Markdown.

### Persiapan

Sumber data: Dataset yang digunakan berisi informasi demografis, gaji, dan faktor-faktor lain terkait pekerjaan karyawan.

Setup environment:
- Python (pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn)
- Google Colaboratory untuk eksplorasi data dan analisis
- Tableau Public untuk business dashboard

## Business Dashboard

Dashboard telah dibuat menggunakan Tableau Public untuk memvisualisasikan faktor-faktor yang mempengaruhi attrition rate karyawan. Dashboard ini mencakup berbagai visualisasi seperti:
- Distribusi attrition berdasarkan faktor utama seperti WorkLifeBalance, MonthlyIncome, dan Department.
- Box plot untuk melihat perbedaan distribusi MonthlyIncome antar karyawan yang bertahan dan keluar.
- Pie chart yang menunjukkan persentase attrition.
- Interaktivitas melalui filter untuk eksplorasi lebih lanjut.
Link Tableau : https://public.tableau.com/views/HR_17397294988500/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

## Conclusion

1. Gaji bulanan memiliki pengaruh signifikan terhadap attrition. Hasil uji hipotesis menunjukkan bahwa karyawan dengan gaji lebih tinggi cenderung memiliki tingkat attrition yang lebih besar.
2. Model prediksi memiliki akurasi 84%, tetapi recall untuk mendeteksi karyawan yang keluar masih rendah. Hal ini menunjukkan bahwa model perlu dioptimalkan agar lebih efektif dalam mendeteksi karyawan yang berisiko keluar.
3. Business dashboard membantu HR dalam memonitor faktor-faktor yang mempengaruhi attrition dan memberikan wawasan untuk pengambilan keputusan.
   
### Rekomendasi Action Items

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.
1. Meningkatkan kesejahteraan karyawan dengan kebijakan gaji yang lebih kompetitif untuk mengurangi tingkat attrition pada karyawan dengan gaji tinggi.
2. Mengembangkan program keterlibatan karyawan guna meningkatkan kepuasan kerja dan menurunkan tingkat keluar.
3. Menggunakan dashboard secara rutin untuk memonitor perkembangan attrition dan mengambil tindakan preventif lebih awal.
