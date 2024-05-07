## 2.1. Original code of broadcast chat.
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
Bagaimana cara menjalankan? <br> 
    Untuk menjalankannya, saya membuka 4 Terminal Vscode dan menjalankan "cargo run --bin server" pada 1 Terminal dan "cargo run --bin client" pada 3 Terminal lainnya. Perintah "cargo run --bin server" untuk menjalankan server dan perintah "cargo run --bin client" untuk menjalankan client.
 
Apa yang terjadi ketika mengetikkan teks pada beberapa client? <br>
    Ketika saya mengetikkan teks atau mengirimkan message dari salah satu client, maka server akan menerima message tersebut, lalu mengirimkan message tersebut ke ketiga client termasuk client yang mengirimkan message tersebut.