                                                               | Variable       |    DATA DIRI     |
                                                               | ---------------| ---------------- |
                                                               | Nama           | Muhammad Maulana |                                          
                                                               | NIM            | 312310475        |
                                                               | Kelas          | TI.23.A.5        |
                                                               | Mata Kuliah    |Bahasa Pemrograman|

## Installation environmet virtual(venv) & Deactivate di visual studio code
- python - m venv praktikum3
- for activate praktikum3/Scripts/activate
- deactivate
## Operating System Used
* [WINDOWS 10](https://www.microsoft.com/software-download/windows10) -You can use this page to download a disc image (ISO file) that can be used to install or reinstall Windows 10.
## command 
 - git add dapat digunakan secara spesifik untuk file tertentu atau direktori, memberikan Anda fleksibilitas untuk memilih perubahan mana yang akan dimasukkan dalam staging 
  area.
 - git commit -m “hi” Untuk menyimpan perubahan yang ada kedalam database repository local
 - git remote add origin https://github.com/Maullynn/praktikum3.git Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada 
   local repository, sehingga dapat diakses oleh banyak user.
 - git push -u origin master/main Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
 - git clone [url] Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working 
   directory).
## labspy02
## Pertama 
- program meminta pengguna untuk memasukkan tiga bilangan menggunakan input(), dan hasilnya disimpan dalam variabel bilangan1, bilangan2, dan bilangan3.
  Kemudian, program memeriksa tiga kondisi menggunakan if:
## pertama
- memeriksa apakah bilangan1 lebih besar dari bilangan2 dan bilangan3. Jika benar, maka bilangan1 adalah yang terbesar.
## kedua
- jika kondisi pertama salah, maka memeriksa apakah bilangan2 lebih besar dari bilangan1 dan bilangan3. Jika benar, maka bilangan2 adalah yang terbesar.
  Jika kedua kondisi sebelumnya salah, maka bilangan3 adalah yang terbesar.Hasil bilangan terbesar ditampilkan menggunakan pernyataan print.
## output
![Screenshot (213)](https://github.com/Maullynn/labspy02/assets/144296695/965ba697-7f4a-41e7-abf4-381da0822bd8)
Dengan demikian, program akan menentukan bilangan terbesar di antara ketiga bilangan yang dimasukkan oleh pengguna dan mencetaknya ke layar.
## labspy03
- LATIHAN1 
- import random: Ini adalah pernyataan untuk mengimpor modul random, yang digunakan untuk menghasilkan bilangan acak.
- n = int(input("Masukkan nilai n: ")): Program ini meminta pengguna untuk memasukkan sebuah nilai n melalui keyboard. Nilai tersebut kemudian dikonversi menjadi integer 
  (bilangan bulat) dan disimpan dalam variabel n.
- count = 0: Variabel count diinisialisasi dengan nilai 0. Variabel ini akan digunakan sebagai penghitung untuk melacak berapa kali bilangan acak telah dihasilkan.
- while count < n:: Ini adalah awal dari loop while. Kode dalam loop ini akan dieksekusi selama nilai count kurang dari n.
- random_number = random.random(): Ini adalah pernyataan yang menghasilkan sebuah bilangan acak antara 0 dan 1 dengan menggunakan fungsi random.random() dari modul random. 
  Hasilnya disimpan dalam variabel random_number.
- if random_number < 0.5:: Program memeriksa apakah random_number kurang dari 0.5. Jika benar, maka bilangan tersebut akan dicetak.
- print(random_number): Jika bilangan acak memenuhi kondisi sebelumnya (kurang dari 0.5), maka bilangan tersebut akan dicetak ke layar.
## OUTPUT
![latihan1](https://github.com/Maullynn/labspy02/assets/144296695/41cae835-436c-4be8-996e-fb8efb4f4ca2)
## LATIHAN 2 
- max_number = None: Variabel max_number diinisialisasi dengan nilai None. 
  Ini digunakan untuk menyimpan bilangan terbesar yang akan dicari nantinya.
- while True:: Ini adalah awal dari loop while yang akan berjalan tanpa 
  henti (selama kondisinya True), sehingga program akan terus meminta 
  pengguna untuk memasukkan bilangan.
- input_number = float(input("Masukkan angka (0 untuk berhenti): "): 
  Program meminta pengguna untuk memasukkan sebuah bilangan desimal. 
  Bilangan yang dimasukkan oleh pengguna disimpan dalam variabel 
  input_number setelah dikonversi menjadi float (bilangan riil).
- if input_number == 0:: Program memeriksa apakah bilangan yang dimasukkan 
  oleh pengguna adalah 0. Jika iya, maka program akan keluar dari loop 
  while 
  dengan pernyataan break, sehingga pengguna dapat menghentikan input 
  dengan 
 memasukkan 0.
- if max_number is None or input_number > max_number:: Program memeriksa 
  apakah nilai max_number saat ini adalah None (belum ada bilangan yang 
  dimasukkan sebelumnya) atau apakah input_number lebih besar dari 
  max_number yang sebelumnya. Jika salah satu kondisi ini terpenuhi, maka 
  max_number akan diubah menjadi input_number.
## OUTPUT
![latihan2](https://github.com/Maullynn/labspy02/assets/144296695/d819effd-aabb-47cd-b9d8-689cd835d93f)
## LATIHAN 3
- total_keuntungan += modal_awal * 0.01: Pada bulan 3, laba 1% dari modal awal ditambahkan ke total_keuntungan.
- total_keuntungan += modal_awal * 0.05: Pada bulan 5, laba 5% dari modal awal ditambahkan ke total_keuntungan.
- total_keuntungan += modal_awal * 0.03: Pada bulan 8, laba 3% dari modal awal ditambahkan ke total_keuntungan.
- print("Total Keuntungan selama 8 bulan adalah: Rp", total_keuntungan): Ini adalah perintah cetak yang digunakan untuk mencetak hasil perhitungan total keuntungan selama 8 
  bulan ke layar. Pesan ini juga mencantumkan jumlah keuntungan dalam bentuk mata uang (Rupiah).
## OUTPUT
![latihan3](https://github.com/Maullynn/labspy02/assets/144296695/3a50a321-8006-4fbc-9231-43accf3814ec)



## pengerjaan
![Screenshot (212)](https://github.com/Maullynn/labspy02/assets/144296695/f7cbe81f-699c-4ae5-ac24-2ffbbdd296b7)
