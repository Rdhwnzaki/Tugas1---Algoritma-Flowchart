Tugas 1
1. Mulai
2. Menginput teks dan cek apakah teks yang diinputkan berupa string atau bukan
3. Jika 'bukan' maka harus menginput teks kembali
4. Jika 'ya' maka x = teks.length - 1
5. Jika x >= 0 maka hasil = hasil + teks[x] dan x - 1
6. Perulangan akan terus terjadi sampai nilai x = 0
7. Jika hasil dan teks bernilai sama maka outputnya 'Palindrom'
8. Jika hasil dan teks nilainya tidak sama maka outputnya 'Bukan Palindrom'
9. Selesai

Tugas 2
1. Mulai
2. Membuat function reverseWords(kalimat)
3. Membuat variabel 'kata' yang berisi kalimat.split(' ') yang berguna untuk memecah isi dari parameter 'kalimat' menjadi array
4. Membuat variabel 'revKata' yang berisi kata.reverse() yang berguna untuk membalikan nilai array yang tadi sudah dipecah
5. Return revKata.join(' ') berguna untuk menggabungkan array menjadi string
6. Memanggil function reverseWords('kalimat') dan memasukan nilai dari parameter 'kalimat' yang berupa string
7. Jalankan program dan outputnya adalah isi dari parameter 'kalimat' yang nilai nya sudah dibalikan
8. Selesai
