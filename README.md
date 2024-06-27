**Klasifikasi Uang Rupiah Berbahan Kertas Menggunakan Metode Convolutional Neural Network (CNN) - Google Collab**

    class_list = os.listdir(train_dir)
        for j in range(len(class_list)):
            if classes[0][j] > 0.8:  # Menggunakan threshold 0.5 untuk menentukan kelas
                print('Gambar yang ditampilkan adalah', class_list[j], 'ribu rupiah')
                break

![image](https://github.com/rvln/Klasifikasi-uang-rupiah/assets/113340042/b9de6867-ecb9-4343-a63d-e409402cb75b)



Metode :
  1. CNN
  2. Equalization Histogram
  3. Sharpen

**NOTE (WAJIB DI BACA SEBELUM MENGGUNAKAN FILE DIATAS!!!**
- Untuk menggunakan file ipynb tersebut, anda harus menggunakan Google Collab.
- Wajib Membuat 4 Folder Utama (Bahan/Source, Latih/Train, Validasi/Validation, Proses/Process)
- Wajib membuat 2 sub-direktori untuk setiap **'Folder Utama'** (kecuali folder Proses), yaitu folder **'seratus'** dan **'limapuluh'**
- Wajib membuat 2 sub-direktori untuk **'Folder Proses'** dengan masing-masing sub-direktori terdapat 2 folder, yaitu **'seratus'** dan **'limapuluh'**
- [Deskripsi] Folder Bahan untuk file mentah/raw files. (Wajib diisi dengan maksimal 100 dataset setiap mata uang)
- [Deskripsi] Folder Latih untuk file yang akan digunakan sebagai modelling dan testing. (Wajib dibiarkan kosong)
- [Deskripsi] Folder Validasi untuk file yang akan digunakan untuk memantau dan melakukan pengecekan agar tidak terjadinya overfitting pada pelatihan. (Wajib dibiarkan kosong)
- [Deskripsi] Folder Proses untuk file yang telah diproses menggunakan Ekualisasi Histogram. (wajib dibiarkan kosong)
- Jika hasil dari _**'accuracy, loss, val_accuracy'**_ pada visualisasi menyentuh dibawah 0.9, maka bisa dilakukan **'restart session and running all'** pada navbar runtime.


**DATASET**

![image](https://github.com/rvln/Klasifikasi-uang-rupiah/assets/113340042/6a2f5e1c-ca7b-48fa-9dcc-68456a412f12)


**DATASET > Bahan**

![image](https://github.com/rvln/Klasifikasi-uang-rupiah/assets/113340042/88db0e4e-6d58-4c76-abc5-3a11d4e7e5fc)


**Dataset > Latih**

![image](https://github.com/rvln/Klasifikasi-uang-rupiah/assets/113340042/d6cde3d5-2398-48be-b7a4-b5f506b62801)


**Dataset > Validasi**

![image](https://github.com/rvln/Klasifikasi-uang-rupiah/assets/113340042/83bb2c4e-f33e-46d0-9fee-6c1cbaf3e39d)


**Dataset > Proses**

![image](https://github.com/rvln/Klasifikasi-uang-rupiah/assets/113340042/5c7c577d-1042-48af-8de7-5d72a4ffcb56)



**Dataset > Proses > Latih**

![image](https://github.com/rvln/Klasifikasi-uang-rupiah/assets/113340042/7088f790-50f8-4d08-8d81-a914eef91bfd)


**Dataset > Proses > Validasi**

![image](https://github.com/rvln/Klasifikasi-uang-rupiah/assets/113340042/8bcf94a9-e2a6-4cc5-b3d3-c034a8b35c86)
