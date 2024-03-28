# Task
## Task 1


## Task 2


## Task 3
### Cara pengerjaan
#### Problem a
Script pertama yaitu minute_log.sh yang ada pada task-3. Untuk hasil run dari minute_log.sh sudah saya letakkan di /resource/metrics_{%Y%m%d%H%M%S}.
Pada awal kode tersebut saya membuat beberapa variabel untuk menyimpan waktu saat ini dan tujuan direktori yang akan memudahkan saya untuk membuat file log nantinya. Saya juga membuat 3 variabel untuk menyimpan hasil awk dari free -m dan juga du -sh yang kemudian saya menggabungkan semuanya dan dimasukkan ke dalam 1 variabel yang bernama allMetrics.

Script dirun kemudian akan menghasilkan sebuah file log yang sesuai dengan jam saat script tersebut dirun yang akan disimpan pada /home/$USER/metrics
- Hasil screeshot
  ![3a](task-3/3a.png)
  
#### Problem b
Untuk konfigurasi crontabnya terdapat pada file /task-3/crontab

#### Problem c
Script ini digunakan untuk mengambil seluruh data yang ada pada file yang terbuat dalam kurun jam tertentu. Pada script ini saya menggunakan awk untuk mendapatkan isi dari file tersebut yang kemudian dioperasikan setelah mendapatkan seluruh data dari file yang ada pada jam tertentu. Hasil dari run script ini diletakkan pada direktori yang sama dengan file log yang terbuat pada tiap menitnya yaitu di direktori /home/$USER/metrics.
- Hasil screenshot
  ![3c](task-3/3c.png)
## Task 4


