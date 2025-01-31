# End-of-Service-Life Phase

Fase End of Service Life (EoSL) adalah tahap di mana sebuah produk data dianggap sudah tidak akan dilanjutkan lagi pengembangannya. Hal ini dapat disebabkan oleh beberapa faktor, seperti tidak ada lagi kebutuhan pengguna, biaya pengelolaan yang terlalu tinggi, atau ketidaktersediaan sumber daya manusia untuk mengelola produk data tersebut. Pada fase ini, penting untuk memastikan bahwa data dan metadata diarsipkan dengan benar dan semua proses terkait dilakukan dengan baik.

![End of Service Life Phase Flow](media/eosl_phase.jpg ':size=100%')


## Alur Pekerjaan

1. **Archive Data**
   - **Deskripsi:** Mengarsipkan data yang terkait dengan produk data yang akan dihentikan. Ini memastikan bahwa data tetap tersedia untuk referensi di masa mendatang jika diperlukan.
   - **Output:** Data Archive
   - **Peran:** Data Engineer (Bertanggung Jawab)

2. **Archive Metadata**
   - **Deskripsi:** Mengarsipkan metadata yang terkait dengan produk data untuk memastikan bahwa informasi tentang data tetap tersedia.
   - **Output:** Datahub Metadata
   - **Peran:** Data Engineer (Bertanggung Jawab)

3. **Freeze Access Control List (Read Only Mode)**
   - **Deskripsi:** Membekukan daftar kontrol akses untuk produk data yang dihentikan, sehingga data hanya dapat diakses dalam mode baca.
   - **Output:** Daftar Kontrol Akses yang Dibatasi
   - **Peran:** DataOps (Bertanggung Jawab)

4. **Write End of Service Life (EoSL) Report**
   - **Deskripsi:** Menyusun laporan EoSL yang merangkum alasan penghentian produk data dan langkah-langkah yang diambil selama proses pengarsipan.
   - **Output:** Wiki Docs: EoSL Report
   - **Peran:** Data Governance Analyst (Bertanggung Jawab)

5. **PII Data Destruction**
   - **Deskripsi:** Menghancurkan data pribadi yang dapat diidentifikasi (PII) untuk memastikan kepatuhan terhadap regulasi privasi data.
   - **Output:** Data PII yang Dihancurkan
   - **Peran:** Data Engineer (Bertanggung Jawab)

## Tanggung Jawab Peran

- **Data Engineer**
  - Bertanggung jawab untuk mengarsipkan data dan metadata serta menghancurkan data PII.
  - Memastikan bahwa semua data yang diperlukan diarsipkan dengan benar dan aman.

- **DataOps**
  - Bertanggung jawab untuk membekukan daftar kontrol akses dan memastikan bahwa data hanya dapat diakses dalam mode baca.
  - Mengelola proses pengarsipan dan memastikan bahwa semua langkah diikuti dengan benar.

- **Data Governance Analyst**
  - Bertanggung jawab untuk menyusun laporan EoSL dan mendokumentasikan semua langkah yang diambil selama proses penghentian produk data.
  - Memastikan bahwa semua kebijakan dan prosedur diikuti selama fase ini.

## Tantangan dan Mitigasi Risiko

1. **Tantangan: Kehilangan Data Penting**
   - **Mitigasi:** Melakukan audit menyeluruh sebelum pengarsipan untuk memastikan bahwa semua data penting telah diidentifikasi dan diarsipkan.

2. **Tantangan: Ketidakpahaman Pengguna tentang Proses EoSL**
   - **Mitigasi:** Mengkomunikasikan dengan jelas kepada semua pemangku kepentingan tentang proses EoSL dan alasan di balik penghentian produk data.

3. **Tantangan: Kepatuhan terhadap Regulasi Privasi Data**
   - **Mitigasi:** Memastikan bahwa semua langkah untuk menghancurkan data PII dilakukan sesuai dengan regulasi yang berlaku.

4. **Tantangan: Proses Pengarsipan yang Tidak Efisien**
   - **Mitigasi:** Mengembangkan prosedur yang jelas dan terstandarisasi untuk pengarsipan data dan metadata.

5. **Tantangan: Ketidakpastian dalam Pengelolaan Data yang Dihentikan**
   - **Mitigasi:** Menyusun rencana pengelolaan yang jelas untuk data yang diarsipkan, termasuk siapa yang bertanggung jawab untuk mengelola data tersebut di masa mendatang.

Fase ini sangat penting untuk memastikan bahwa produk data yang dihentikan dikelola dengan baik dan bahwa semua data yang relevan diarsipkan dengan aman untuk referensi di masa mendatang.