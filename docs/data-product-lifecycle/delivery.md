# Delivery Phase

Fase Delivery dimulai ketika produk engineering sudah mulai terbentuk. Pada fase ini, dilakukan berbagai unit test dan integration testing, serta pembuatan access control policy dan finalisasi data contract. Fase ini sangat penting untuk memastikan bahwa produk data siap digunakan dan memenuhi semua persyaratan yang ditetapkan.


![Delivery Phase Flow](media/delivery_phase.jpg ':size=100%')

## Alur Pekerjaan

1. **Create Access Role Policy**
   - **Deskripsi:** Menyusun kebijakan akses yang mendefinisikan peran dan hak akses pengguna terhadap data.
   - **Output:** Kebijakan Akses yang Ditetapkan
   - **Peran:** DataOps (Bertanggung Jawab)

2. **Map User to Role**
   - **Deskripsi:** Memetakan pengguna ke peran yang sesuai berdasarkan kebijakan akses yang telah dibuat.
   - **Output:** Pemetaan Pengguna ke Peran
   - **Peran:** DataOps (Bertanggung Jawab)

3. **Write Policy and Role Mapping**
   - **Deskripsi:** Menyusun dokumen yang menjelaskan kebijakan dan pemetaan peran.
   - **Output:** Dokumen Kebijakan dan Pemetaan Peran
   - **Peran:** Data Governance Analyst (Bertanggung Jawab)

4. **Finalize Data Contract**
   - **Deskripsi:** Menyelesaikan kontrak data yang mendefinisikan hak dan kewajiban antara penyedia data dan pengguna data.
   - **Output:** Kontrak Data yang Ditetapkan
   - **Peran:** Data Architect (Bertanggung Jawab)

5. **User Training**
   - **Deskripsi:** Melakukan pelatihan untuk pengguna tentang cara menggunakan produk data dan memahami kebijakan akses.
   - **Output:** Materi Pelatihan
   - **Peran:** Data Governance Analyst (Bertanggung Jawab)

6. **Publication**
   - **Deskripsi:** Mempublikasikan dokumentasi dan materi pelatihan dalam berbagai format untuk akses pengguna.
   - **Output:** Publikasi dalam Berbagai Format
   - **Peran:** Data Governance Analyst (Bertanggung Jawab)

7. **Run Initial Data Quality Test**
   - **Deskripsi:** Melakukan pengujian kualitas data awal untuk memastikan bahwa data memenuhi standar yang ditetapkan.
   - **Output:** Laporan Kualitas Data
   - **Peran:** Data Quality Analyst (Bertanggung Jawab)

## Tanggung Jawab Peran

- **DataOps**
  - Bertanggung jawab untuk menyusun dan mengimplementasikan kebijakan akses serta memetakan pengguna ke peran yang sesuai.
  - Mengelola proses pengujian dan memastikan bahwa semua komponen berfungsi dengan baik.

- **Data Governance Analyst**
  - Bertanggung jawab untuk menulis kebijakan dan pemetaan peran, serta melakukan pelatihan pengguna.
  - Mengawasi publikasi dokumentasi dan materi pelatihan.

- **Data Architect**
  - Bertanggung jawab untuk menyelesaikan kontrak data dan memastikan bahwa semua persyaratan teknis terpenuhi.

- **Data Quality Analyst**
  - Bertanggung jawab untuk melakukan pengujian kualitas data dan menghasilkan laporan yang memberikan wawasan tentang kualitas data.

## Tantangan dan Mitigasi Risiko

1. **Tantangan: Kualitas Data yang Buruk**
   - **Mitigasi:** Melakukan pengujian kualitas data secara menyeluruh sebelum peluncuran dan menerapkan proses pembersihan data.

2. **Tantangan: Ketidakjelasan dalam Kebijakan Akses**
   - **Mitigasi:** Melibatkan pemangku kepentingan dalam proses penyusunan kebijakan akses untuk memastikan bahwa semua kebutuhan dipahami dan dipenuhi.

3. **Tantangan: Kurangnya Pelatihan Pengguna**
   - **Mitigasi:** Menyusun program pelatihan yang komprehensif dan menyediakan materi yang mudah diakses untuk pengguna.

4. **Tantangan: Masalah dalam Integrasi Sistem**
   - **Mitigasi:** Melakukan pengujian integrasi secara menyeluruh dan memiliki rencana pemulihan untuk menangani masalah yang mungkin muncul.

5. **Tantangan: Komunikasi yang Buruk dalam Tim**
   - **Mitigasi:** Mengadakan pertemuan rutin untuk memastikan semua anggota tim memiliki pemahaman yang sama tentang kemajuan dan tantangan yang dihadapi.

Fase ini sangat penting untuk memastikan bahwa produk data yang dikembangkan tidak hanya berfungsi dengan baik tetapi juga memenuhi semua persyaratan yang ditetapkan untuk penggunaan yang efektif.