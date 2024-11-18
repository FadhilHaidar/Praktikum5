# Tugas Praktikum

Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:

- Program dibuat dengan menggunakan Dictionary

- Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)

- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)

- Buat flowchart dan penjelasan programnya pada README.md.

- Commit dan push repository ke github.

# Tampilan Program

1. Flowchart


2. Program Python

![image](https://github.com/user-attachments/assets/60ce470b-1d7c-4ef7-b528-312b5b432375)

![image](https://github.com/user-attachments/assets/236933c6-e5dd-4b1b-9d5c-8b9cabaf92ca)

![image](https://github.com/user-attachments/assets/7fc8952a-3524-4c4a-b955-d32279fbb4bb)

![image](https://github.com/user-attachments/assets/46225b98-acc6-4fdd-b6ea-ebcd80e9a079)

3. Penjelasan

  - Inisialisasi Dictionary:

    - Membuat sebuah dictionary data_mahasiswa untuk menyimpan data mahasiswa.
    
    - Kunci dictionary adalah NIM, dengan nilai berupa dictionary berisi nama, tugas, uts, uas, dan nilai akhir.

  - Tampilkan Menu:

      ![image](https://github.com/user-attachments/assets/7b2b66e0-0ae9-47d6-84d1-261e58e55f23)

    - Program menampilkan menu pilihan: Lihat, Tambah, Ubah, Hapus, Cari, dan Keluar.
    
    - Pengguna memilih opsi yang diinginkan.

  - Tambah Data:

    - Program meminta input NIM, Nama, Nilai Tugas, Nilai UTS, dan Nilai UAS.
    
    - Program menghitung nilai_akhir menggunakan rumus:
    
        Nilai Akhir = (Tugas × 30%) + (UTS × 35%) + (UAS × 35%)
    
    - Data dimasukkan ke dalam dictionary.
   
      ![image](https://github.com/user-attachments/assets/5154b485-3893-487d-ba4b-1705a755de0b)

  - Ubah Data:

    - Program meminta NIM untuk mencari data yang akan diubah.

    - Jika ditemukan, program meminta input nilai baru (Tugas, UTS, UAS) dan memperbarui data.
    
    - Nilai Akhir dihitung ulang.
   
      ![image](https://github.com/user-attachments/assets/48d22f5b-b659-4e5b-be59-5842e37fa231)

  - Hapus Data:

    - Program meminta NIM untuk mencari data yang akan dihapus.
    
    - Jika ditemukan, data dihapus dari dictionary.
   
      ![image](https://github.com/user-attachments/assets/3a0015e9-94ab-4ca8-8ea3-d335307854f2)

  - Tampilkan Data:

    - Program mencetak daftar data mahasiswa dalam format tabel.
   
      ![image](https://github.com/user-attachments/assets/93f87337-135e-453a-8052-9184f951bb3f)

  - Cari Data:

    - Program meminta NIM untuk mencari data.
    
    - Jika ditemukan, data mahasiswa ditampilkan.
   
      ![image](https://github.com/user-attachments/assets/a79d0a96-9d6a-4401-a337-ba529390dff5)

  - Keluar:

    - Program berhenti jika pengguna memilih opsi keluar.
   
      ![image](https://github.com/user-attachments/assets/f5f19fc3-b667-45f8-b89e-498c1e93e5f1)

4. Input & Output

   ![image](https://github.com/user-attachments/assets/466b53b3-77bc-4ae5-badc-f33d40cf2d41)
