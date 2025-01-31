# Berkontribusi menyusun Playbook


Untuk berkontribusi dalam penyusunan dokumen playbook ini, Anda dapat menggunakan Git dengan mengikuti langkah-langkah berikut:


## Instalasi Git

### Instalasi Git untuk Windows

1. Buka halaman download Git di [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Klik tombol "Download" untuk mengunduh installer Git
3. Klik dua kali pada file installer yang diunduh untuk menjalankan proses instalasi
4. Ikuti langkah-langkah yang diberikan oleh wizard instalasi untuk menyelesaikan proses instalasi

### Instalasi Git untuk Linux

1. Buka terminal dan jalankan perintah berikut untuk menginstal Git
```bash
sudo apt install git
```

2. Cek apakah Git sudah terinstall dengan menggunakan perintah 
```bash
git --version
```

### Instalasi Git untuk Mac

1. Buka terminal dan jalankan perintah berikut untuk menginstal Git
```bash
brew install git
```

2. Cek apakah Git sudah terinstall dengan menggunakan perintah 
```bash
git --version
```

## Clone Repositori

1. Clone repositori Git ini dengan menggunakan perintah 

```bash
git clone https://github.com/jabardigitalservice/data-product-management-playbook.git
```

2. Buat branch baru dengan menggunakan perintah 
```bash
git branch <nama_branch_baru>
```

3. Lakukan perubahan pada branch yang baru dibuat

4. Lakukan commit perubahan dengan menggunakan perintah 
```bash
git commit -m "pesan commit"
```

5. Buat merge request dengan menggunakan perintah 
```bash 
git push origin <nama_branch_baru> 
```
6. Buka halaman repositori di Github dan klik tombol "**New pull request**"

7. Pilih branch yang baru dibuat sebagai branch yang akan digunakan untuk merge request

8. Tulis judul dan deskripsi untuk merge request

9. Klik tombol "Create pull request" untuk membuat merge request

10. Setelah merge request disetujui, hapus branch yang baru dibuat dengan menggunakan perintah 

```bash
git branch -d <nama_branch_baru>
```
## Menggunakan Git Flow
Anda juga dapat menggunakan ***Git Flow*** dengan mengikuti langkah-langkah berikut:

1. Buat branch fitur baru dengan menggunakan perintah 
```bash 
git flow feature start <nama_branch_fitur_baru>
```

2. Lakukan perubahan pada branch fitur yang baru dibuat

3. Buat merge request dengan menggunakan perintah 
```bash
git flow feature finish <nama_branch_fitur_baru>
```

4. Setelah merge request disetujui, hapus branch fitur yang baru dibuat dengan menggunakan perintah 
```bash 
git flow feature delete <nama_branch_fitur_baru>
```
