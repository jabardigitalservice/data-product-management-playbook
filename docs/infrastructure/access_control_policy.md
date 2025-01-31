# Manajemen Access Policy dalam Pengelolaan Data Product

Manajemen Access Policy adalah proses yang penting dalam pengelolaan data product untuk memastikan bahwa hanya pengguna yang berwenang yang dapat mengakses data sensitif. Proses ini dikontrol oleh Data Governance Officer, yang bertanggung jawab untuk menetapkan dan mengawasi kebijakan akses. Semua akses ke database dan server dilakukan melalui bastion host menggunakan software Teleport.io, yang menyediakan keamanan tambahan dan kontrol akses yang lebih baik.

## Alur Kerja Manajemen Access Policy

1. **Penetapan Kebijakan Akses**
   - Data Governance Officer menetapkan kebijakan akses yang jelas, termasuk siapa yang dapat mengakses data dan dalam kondisi apa.

2. **Pengaturan Bastion Host**
   - Bastion host dikonfigurasi untuk mengelola semua akses ke database dan server. Teleport.io digunakan untuk mengamankan koneksi dan mengelola sesi pengguna.

3. **Pendaftaran Pengguna**
   - Semua pengguna yang memerlukan akses harus mendaftar dan mendapatkan persetujuan dari Data Governance Officer.

4. **Akses Data**
   - Pengguna mengakses data melalui bastion host. Semua akses dicatat, termasuk timestamp dan data yang diakses.

5. **Monitoring dan Audit**
   - Akses pengguna dipantau secara berkala untuk memastikan kepatuhan terhadap kebijakan akses. Audit dilakukan untuk meninjau log akses.

6. **Pembaruan Kebijakan**
   - Kebijakan akses diperbarui secara berkala berdasarkan kebutuhan bisnis dan perubahan regulasi.

## Diagram Alur Kerja

## Peran yang Terlibat

- **Data Governance Officer**
  - Bertanggung jawab untuk menetapkan dan mengawasi kebijakan akses.
  - Memastikan bahwa semua pengguna yang memerlukan akses telah terdaftar dan disetujui.

- **Data Engineer**
  - Mengelola konfigurasi bastion host dan integrasi dengan Teleport.io.
  - Memastikan bahwa semua akses ke database dan server aman.

- **Pengguna**
  - Mengakses data sesuai dengan kebijakan yang ditetapkan.
  - Mematuhi semua prosedur yang terkait dengan akses data.

## Kesimpulan

Manajemen Access Policy yang efektif sangat penting untuk melindungi data sensitif dan memastikan bahwa hanya pengguna yang berwenang yang dapat mengakses informasi tersebut. Dengan menggunakan bastion host dan Teleport.io, organisasi dapat meningkatkan keamanan dan kontrol akses, sambil memastikan bahwa semua aktivitas akses dicatat dan diaudit secara berkala.
