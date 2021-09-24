# Jarkom-Modul-1-B05-2021
# Praktikum Modul 1 20 September 2021
### 1. Sebutkan webserver yang digunakan pada "ichimarumaru.tech"!
**Display Filter:**
```http.host=="ichimarumaru.tech" && http.request```
<img src="Screenshot/hasil-filter-no-1.jpg" width="800">  
->lalu kemudian klik kanan pada paket yang didapat lalu dilakukan follow-> TCP stream
<img src="Screenshot/tcp-stream-no-1.jpg" width="800">  
->kemudian mendapat informasi server
<img src="Screenshot/server-no-1.jpg" width="800">  
web server yang digunakan adalah nginx/1.18.0 (Ubuntu)

### 2. Temukan paket dari web-web yang menggunakan basic authentication method!
**Display Filter:**
```http.authbasic```
<img src="Screenshot/hasil-filter-no-2.jpg" width="800">

### 7. Ada 500 file zip yang disimpan ke FTP Server dengan nama 0.zip, 1.zip, 2.zip, ..., 499.zip. Simpan dan Buka file pdf tersebut. (Hint = nama pdf-nya "Real.pdf")
**Display Filter:**
```ftp-data contains "Real.pdf"```
<img src="Screenshot/hasil-filter-no-7.jpg" width="800"> 

-> lalu dapat dipilih salah satu paket kemudian di klik kanan pada paket tersebut kemudian follow-> TCP Stream
<img src="Screenshot/tcp-stream-no-7.jpg" width="800"> 

-> setelah itu pada bagian show data as dibuat ke RAW lalu di Save as dengan nama file misal Jarkom dengan format zip jadi "Jarkom.zip"
<img src="Screenshot/save-as-no-7.jpg" width="800"> 

-> setelah itu membuka file hasil download tersebut
<img src="Screenshot/isi-zip-no-7.png" width="800">

-> kemudian saat dibuka filenya akan menampilkan halaman berikut
<img src="Screenshot/pdf-no-7.jpg" width="800"> 

