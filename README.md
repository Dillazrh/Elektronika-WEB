# Tema : Aplikasi IOT dasar dan penerapan
# Judul : Menyalakan lampu LED menggunakan HP koneksi WIFI lokal
# Nama : Nadilla Ristya Azzahra

# Alat Bahan
Esp 32
Laptop/Komputer + Software Arduino IDE
Kabel micro USB
Resistor 220 - 330 ohm
Jumper wires male to female
Lampu Led 3mm
Project board/Bearboard

# LANGKAH KERJA :
1. Langkah pertama anda harus menginstal software Arduino IDE pada komputer anda. 
2. Setelah menginstal software Arduino IDE dibutuhkan juga library ESP32, maka anda harus menginstal librarynya terlebih dahulu. (https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json)
3. Lalu untuk menginstal library ESP32, maka masukkan link library pada menu preference pada  Arduino IDE (cara penginstalan library dan penambahan board ada pada file di atas) lalu tekan tombol "OK".
4. Jika librarynya sudah terinstal dan ditambahkan, maka anda bisa mulai memasukkan programnya (contoh program ada pada file "LED_ESP32" diatas). 
5. Langkah berikutnya sambungkan ESP32 pada port komputer anda menggunakan kabel micro usb. 
6. Lalu upload program yang sudah anda masukkan tadi, agar terkoneksi dengan esp32 . 
7. Jika sudah terupload maka tunggu beberapa saat hingga kotak putih di bagian kanan bawah Arduino IDE terisi warna hijau sepenuhnya. 
8. Setelah itu sambungkan wifi pada hp anda dengan jaringan wifi yang sudah terprogram tadi dan masukkan password yang sama dengan program tadi (contoh ada di file atas). 
9. Jika sudah terkoneksi, anda bisa membuka serial monitor yang ada di Arduino IDE dan dapat mengetahui alamat IP dari jaringan wifinya. 
10. Lalu kalian buka web di hp anda pada aplikasi chrome  dan masukan alamat IP tadi hingga muncul laman berisi tulisan on berwarna hijau (seperti contoh di file atas). 
11. Pada web itulah yang membantu anda untuk mengoperasikan lampu LED agar dapat hidup (ON) dan mati (OFF) sesuai keinginan anda. 
Selamat mencoba dan semoga berhasil ˶ᵔ ᵕ ᵔ˶

# SKEMA WIRING/ RANGKAIAN :
1. Langkah pertama hubungkan jalur negatif pada project board ke GND ESP32 menggunakan kambel jumper. 
2. Kemudian susun LED pada project board dengan rapi. 
3. Setelah itu hubungkan salah satu kaki resistor dengan kaki katoda LED dan satu kaki resistor lainnya dihubungkan pada jalur negatif project board yang sudah terhubung pada GND ESP 32, lakukan hal yang sama pada LED lainnya. 
4. Lalu kaki anoda LED di hubungkan dengan pin dari ESP32 (contoh pin yg digunakan 25,26,27,32,33).
5. Dan terakhir hubungkan semua kaki resistor ke jalur negatif pada project board. 

 Untuk lebih jelaskan lihat gambar yang tertera di file atas.
