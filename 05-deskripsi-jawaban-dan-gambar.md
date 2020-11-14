Pengamanan Server sangat penting agar tidak terjadi kebocoran file ataupun dokumen, menurut saya berikut ini adalah cara bagaimana
kita memberikan proteksi atau pengamanan terhadap server khususnya dalam ubuntu :

Metode Auth SSH Key pada Host/Server
1. Pertama buka terminal Ubuntu lalu Ketikan perintah "sudo ssh-keygen" lalu Enter, tekan enter kembali hingga muncul seperti gambar
dibawah ini .

![05](https://user-images.githubusercontent.com/20898999/99140921-6fe2d600-2678-11eb-9cb7-d2afdf98ba5c.PNG)

2. Setelah itu copy isi dari file id_rsa.pub dengan perintah sebagai berikut "sudo cat /root/.ssh/id_rsa.pub". Maka akan muncul kode
seperti di bawah ini :

![05a](https://user-images.githubusercontent.com/20898999/99141015-424a5c80-2679-11eb-8ac1-d241b1e9883e.PNG)

3. Setelah itu copy kode dengan warna kuuning tersebut, laluke store public key ssh yang sudah di generate. dan buat file dengan nama
"authorized_keys" dengan perintah "sudo touch authorized_keys dan berikan lagi perintah "sudo nano authorized_keys"

![05b](https://user-images.githubusercontent.com/20898999/99141816-85103280-2681-11eb-8361-1c0368291c18.PNG)

4. Dan Paste kode yang sudah di copy tadi kedalam terminal dan ketika sudah masukan perintah ctrl+X dan ctrl+Y

![05c](https://user-images.githubusercontent.com/20898999/99141854-d5879000-2681-11eb-9744-8d1b373fa566.PNG)

5. Maka ketika login kembali akan muncul Message atau Pesan seperti dibawah dengan login kembali ke server

![05d](https://user-images.githubusercontent.com/20898999/99141879-11225a00-2682-11eb-8e3f-482990aa06b9.PNG)
