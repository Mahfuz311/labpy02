# Latihan 3: Buat program python untuk kasus berikut:
Nama : Mahfuz Fauzi

NIM : 312410412

Kelas : TI.24.A.3

## Kasus 1: Program Pemesanan Tiket Bioskop

Buat program yang menghitung harga tiket bioskop. Tiket reguler berharga Rp50.000,
sedangkan tiket VIP berharga Rp100.000. Jika user memiliki kartu member, mereka
mendapatkan diskon 20% dari harga tiket. Program ini harus meminta tipe tiket dan status
member dari user, lalu menghitung total harga yang harus dibayar.

### Petunjuk:
● Gunakan if else dan operator ternary.

### Hasil eksekusi program

![Screenshot 2024-10-26 143922](https://github.com/user-attachments/assets/e48c9b86-ac89-4ec8-bfc3-f2a5e6defbcd)

### Penjelasan:
● Harga Tiket: Menyimpan harga tiket reguler dan VIP.

● Input: Meminta pengguna untuk memasukkan tipe tiket dan status member.

● Validasi Tipe Tiket: Menggunakan if-elif-else untuk memeriksa tipe tiket.

● Total Harga: Menghitung total harga menggunakan operator ternary:

● Jika pengguna memiliki kartu member (member == "ya"), harga dikurangi diskon 20%.

● Jika tidak, harga tetap sama.

● Output: Menampilkan total harga yang harus dibayar.

### Flowchart nya

![Flowchart Tiket Bioskop drawio](https://github.com/user-attachments/assets/4dd310ed-2128-470b-b0ab-4aa597148c89)

## Kasus 2: Program Kalkulator Sederhana

Buat program kalkulator yang menerima dua angka dan satu operator aritmatika dari pengguna (penjumlahan, pengurangan, perkalian, atau pembagian). Program akan menghitung hasil sesuai dengan operator yang dipilih.

### Petunjuk
● Gunakan if elif else untuk menentukan operasi aritmatika.

### Hasil Eksekusi Program

![Screenshot 2024-10-27 125031](https://github.com/user-attachments/assets/94ff9db9-cef0-4342-a674-96664addd3bf)

### Penjelasan
       ● Program meminta pengguna untuk memasukkan dua angka dan satu operator.

       ● Menggunakan if, elif, dan else untuk memeriksa operator yang dimasukkan dan melakukan operasi yang sesuai.

       ● Jika operator yang dimasukkan tidak valid, program akan menampilkan pesan error.

### Contoh Interaksi
● Jika Anda memasukkan:

       ● Angka pertama: 10
       
        ● Operator: +
        
       ● Angka kedua: 5

  
Maka outputnya akan menjadi:

  Hasil: 10.0 + 5.0 = 15.0

### Flowchart Program Kalkulator

1. Mulai

       ● Titik awal program.
2. Input Angka Pertama

       ● Minta pengguna memasukkan angka pertama.
3. Input Operator

       ● Minta pengguna memasukkan operator aritmatika (+, -, *, /).
4. Input Angka Kedua

       ● Minta pengguna memasukkan angka kedua.
5. Cek Operator

       ● Apakah operator sama dengan +?
              ● Jika ya, lakukan penjumlahan.
              ● Jika tidak, lanjut ke langkah berikutnya.
6. Cek Operator

       ● Apakah operator sama dengan -?
              ● Jika ya, lakukan pengurangan.
              ● Jika tidak, lanjut ke langkah berikutnya.
7. Cek Operator

       ● Apakah operator sama dengan *?
              ● Jika ya, lakukan perkalian.
              ● Jika tidak, lanjut ke langkah berikutnya.
8. Cek Operator

       ● Apakah operator sama dengan /?
              ● Jika ya, cek apakah angka kedua tidak sama dengan 0.
                     ● Jika tidak sama dengan 0, lakukan pembagian.
                     ● Jika sama dengan 0, tampilkan pesan error: "Error: Pembagian dengan nol tidak diizinkan."
              ● Jika tidak, tampilkan pesan error: "Error: Operator tidak valid."
9. Tampilkan Hasil

       ● Tampilkan hasil perhitungan berdasarkan operasi yang dilakukan.
10. Selesai

       ● Akhiri program.

### Flowchart nya

![Flowchart Kalkulator drawio](https://github.com/user-attachments/assets/22764f74-7cd9-4624-a864-8497978f150b)
