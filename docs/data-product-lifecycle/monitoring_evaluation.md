# Monitoring and Evaluation Phase

Fase Monitoring dan Evaluasi adalah tahap di mana kualitas data dan kinerja sistem dipantau secara berkelanjutan. Pada fase ini, tim akan mengotomatiskan pengujian kualitas data, mengatur notifikasi, dan menghasilkan laporan untuk memastikan bahwa produk data berfungsi dengan baik dan memenuhi standar yang ditetapkan.


![Monitoring and Evaluation Phase Flow](media/monitoring_evaluation_phase.jpg ':size=100%')


## Alur Pekerjaan

1. **Automate Data Quality Test**
   - **Deskripsi:** Mengotomatiskan pengujian kualitas data untuk memastikan bahwa data yang digunakan selalu memenuhi standar kualitas.
   - **Output:** DataSae Automated Pipeline
   - **Peran:** Data Engineer (Bertanggung Jawab)

2. **Setup Alert and Notification**
   - **Deskripsi:** Mengatur sistem notifikasi untuk memberi tahu tim tentang masalah kualitas data yang terdeteksi.
   - **Output:** Prometheus Alert
   - **Peran:** DataOps (Bertanggung Jawab)

3. **Setup Data Quality Monitoring Dashboard**
   - **Deskripsi:** Membangun dashboard untuk memantau kualitas data secara real-time dan memberikan wawasan kepada tim.
   - **Output:** DataSae Dashboard
   - **Peran:** Data Engineer (Bertanggung Jawab)

4. **Generate Periodic Data Quality Reports**
   - **Deskripsi:** Menghasilkan laporan berkala tentang kualitas data untuk analisis dan pengambilan keputusan.
   - **Output:** DataSae Report
   - **Peran:** Data Quality Analyst (Bertanggung Jawab)

5. **Generate Periodic Cost Report**
   - **Deskripsi:** Menghasilkan laporan biaya berkala untuk memantau pengeluaran terkait data.
   - **Output:** Cost Report
   - **Peran:** Data Analyst (Bertanggung Jawab)

## Tanggung Jawab Peran

- **Data Engineer**
  - Bertanggung jawab untuk mengotomatiskan pengujian kualitas data dan membangun dashboard pemantauan.
  - Memastikan bahwa pipeline otomatis berfungsi dengan baik dan data yang dihasilkan akurat.

- **DataOps**
  - Bertanggung jawab untuk mengatur sistem notifikasi dan memastikan bahwa tim mendapatkan informasi yang tepat waktu tentang masalah kualitas data.

- **Data Quality Analyst**
  - Bertanggung jawab untuk menghasilkan laporan kualitas data dan menganalisis hasil pengujian untuk memberikan wawasan tentang masalah yang mungkin ada.

- **Data Analyst**
  - Bertanggung jawab untuk menghasilkan laporan biaya dan menganalisis pengeluaran terkait data untuk pengambilan keputusan yang lebih baik.

## Tantangan dan Mitigasi Risiko

1. **Tantangan: Kualitas Data yang Buruk**
   - **Mitigasi:** Mengotomatiskan pengujian kualitas data dan melakukan pemantauan secara real-time untuk mendeteksi masalah lebih awal.

2. **Tantangan: Notifikasi yang Tidak Efektif**
   - **Mitigasi:** Mengatur sistem notifikasi yang jelas dan terukur untuk memastikan bahwa tim menerima informasi yang relevan dan tepat waktu.

3. **Tantangan: Dashboard yang Tidak Informatif**
   - **Mitigasi:** Melibatkan pemangku kepentingan dalam desain dashboard untuk memastikan bahwa informasi yang ditampilkan relevan dan berguna.

4. **Tantangan: Laporan yang Tidak Akurat**
   - **Mitigasi:** Melakukan verifikasi dan validasi terhadap data yang digunakan dalam laporan untuk memastikan akurasi.

5. **Tantangan: Ketidakpahaman Tim terhadap Data**
   - **Mitigasi:** Menyediakan pelatihan dan sumber daya untuk tim agar mereka dapat memahami dan menggunakan data dengan lebih baik.

Fase ini sangat penting untuk memastikan bahwa produk data tidak hanya berfungsi dengan baik tetapi juga memberikan nilai yang signifikan bagi organisasi melalui pemantauan dan evaluasi yang berkelanjutan.