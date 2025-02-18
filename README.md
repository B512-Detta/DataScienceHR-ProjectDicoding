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

Sumber data: Dataset yang digunakan berisi informasi demografis, gaji, dan faktor-faktor lain terkait pekerjaan karyawan. Data diambil dari link : https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

## Setup Environment  

### 1. Install Dependencies (Library)
Sebelum menjalankan proyek ini, pastikan Anda memiliki Python 3.9 atau lebih baru.

## Setup Environment - Anaconda
```
conda create --name attrition-analysis python=3.9
conda activate attrition-analysis
pip install -r requirements.txt
```
## Setup Environment - Virtual environment biasa
```
python -m venv env
source env/bin/activate  # Untuk Linux/macOS
env\Scripts\activate  # Untuk Windows
pip install -r requirements.txt
```
### 2. Jalankan Notebook
Setelah environment terinstal, jalankan notebook dengan perintah: jupyter notebook
Lalu buka file ProyekHRDataScience.ipynb dan jalankan semua sel untuk melihat hasil analisis

## Business Dashboard

Dashboard telah dibuat menggunakan Tableau Public untuk memvisualisasikan faktor-faktor yang mempengaruhi attrition rate karyawan. Dashboard ini mencakup berbagai visualisasi seperti:
- Distribusi attrition berdasarkan faktor utama seperti WorkLifeBalance, MonthlyIncome, dan Department.
- Box plot untuk melihat perbedaan distribusi MonthlyIncome antar karyawan yang bertahan dan keluar.
- Pie chart yang menunjukkan persentase attrition.
- Interaktivitas melalui filter untuk eksplorasi lebih lanjut.
Link Tableau : https://public.tableau.com/views/HR_17397294988500/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

## Conclusion
Berdasarkan analisis data, berikut adalah temuan utama terkait **attrition rate** karyawan di perusahaan:  
1. **Gaji Bulanan (Monthly Income) Berpengaruh Signifikan**  
   - Karyawan dengan **gaji lebih rendah** cenderung bertahan lebih lama.  
   - Sementara itu, **karyawan dengan gaji lebih tinggi justru memiliki kemungkinan lebih besar untuk keluar**.  

2. **Faktor Work-Life Balance dan Job Satisfaction**  
   - **Karyawan dengan Work-Life Balance rendah** lebih cenderung melakukan attrition.  
   - **Job Satisfaction yang rendah** juga meningkatkan kemungkinan keluar dari perusahaan.  

3. **Business Travel dan OverTime**  
   - Karyawan yang sering bepergian dinas (**Travel Frequently**) lebih banyak keluar dibanding yang jarang bepergian.  
   - Karyawan yang **sering lembur (OverTime)** juga memiliki tingkat attrition yang lebih tinggi.

4. **Karakteristik Umum Karyawan yang Keluar**  
   - Lebih banyak ditemukan di **Departemen Sales** dan **Research & Development**.  
   - Cenderung memiliki **pengalaman kerja lebih pendek** dan lebih banyak berpindah kerja (**NumCompaniesWorked lebih tinggi**).  
   - Mayoritas berada di level pekerjaan **Junior (Job Level 1-2)**.  
   
### Rekomendasi Action Items
Berdasarkan hasil analisis, berikut beberapa rekomendasi yang dapat diambil oleh perusahaan untuk **mengurangi tingkat attrition**:  
1. **Menyesuaikan Skema Gaji dan Insentif**  
   - Tinjau kembali skema gaji, terutama bagi karyawan dengan **pengalaman tinggi** agar mereka tidak mudah berpindah kerja.  
   - Berikan bonus atau **insentif retensi** bagi karyawan yang telah bekerja lebih lama.  

2. **Meningkatkan Work-Life Balance**  
   - Mengurangi **lembur yang berlebihan** dengan kebijakan kerja yang lebih fleksibel.  
   - Meningkatkan fasilitas dan program kesejahteraan untuk mendukung keseimbangan kerja-kehidupan.  

3. **Membatasi Frekuensi Perjalanan Dinas**  
   - Untuk karyawan yang sering bepergian (**Travel Frequently**), perusahaan dapat menawarkan **opsi kerja jarak jauh atau rotasi tim** untuk mengurangi burnout.  

4. **Meningkatkan Kepuasan Kerja (Job Satisfaction)**  
   - Mengadakan **program pengembangan karir**, pelatihan, dan peluang promosi yang lebih transparan.  
   - Melakukan **survey kepuasan kerja secara berkala** untuk memahami kebutuhan karyawan.  

5. **Fokus pada Departemen dan Jabatan dengan Tingkat Attrition Tinggi**  
   - Memberikan perhatian lebih pada **Departemen Sales dan Research & Development**, karena tingkat attrition mereka lebih tinggi.  
   - Memperbaiki kebijakan pengelolaan karyawan baru dan junior agar mereka lebih termotivasi untuk bertahan.  

