Berikut pembuatan server sederhana Nginx :

1. Pertama buka pada Terminal dan ketikan perintah berikut "sudo apt update"
![08](https://user-images.githubusercontent.com/20898999/99149008-f7066d00-26bd-11eb-9e31-f1e12d961316.PNG)

2. Lalu masukan perintah " sudo apt install nginx ", apabila ada option Y/N pilih Y pada terminal
![image](https://user-images.githubusercontent.com/20898999/99149052-4c427e80-26be-11eb-9988-4286d2345461.png)

3. Setelah itu masukan perintah "sudo systemctl start nginx" dan "sudo systemctl enable nginx" setelah itu masukan perintah lagi "sudo systemctl status nginx"
   maka akan muncul tampilan seperti di bawah 
![08b](https://user-images.githubusercontent.com/20898999/99149130-c115b880-26be-11eb-8121-08d1400f4b64.PNG)

4. Dan masukan perintah secara berkala dari "sudo ufw allow 80/tcp" -> "sudo ufw allow 443/tcp" -> "sudo ufw reload"
![08c](https://user-images.githubusercontent.com/20898999/99149384-3f268f00-26c0-11eb-9b8e-402dfa1662f9.PNG)

5. Buka Browser dan masukan link http://Your-IP-Address pada web browser, jika berhasil akan muncul gambar seperti di bawah
![08d](https://user-images.githubusercontent.com/20898999/99149492-f9b69180-26c0-11eb-9505-2dc3f96e2c44.PNG)
