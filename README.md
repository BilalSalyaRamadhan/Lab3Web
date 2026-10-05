Langkah-Langkah Praktikum & Implementasi
1.	Membuat Dokumen HTML Dasar
Membuat struktur dasar dokumen HTML dengan menyertakan navigasi, elemen header, serta pembungkus dengan ID dan Class selector.
<img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/57a4a619-4559-4e51-b934-0f023fc17493" />

2.	Mendeklarasikan CSS Internal
Menambahkan tag <style> pada bagian <head> dokumen untuk mengatur gaya dasar seperti font, padding, border, dan warna teks pada elemen header dan h1.
<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/23e15575-71c9-48ff-9f86-d196fbb957f0" />

3.	Menambahkan Inline CSS
Menambahkan deklarasi inline CSS langsung pada tag paragraf <p> untuk mengubah gaya pada baris tertentu secara spesifik.
<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/0a3c4516-6b6b-431a-84f7-fdf473831f21" />

4.	Membuat CSS Eksternal
Membuat file CSS terpisah untuk mengatur tata letak navigasi, warna latar belakang, serta efek hover pada menu. File eksternal dihubungkan menggunakan tag <link>.
<img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/e9e18075-a2c4-45bc-9a11-92b4b48dae0a" />
<img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/84e2a266-d52e-436a-a428-58711f85d39b" />

5.	Menambahkan CSS Selector (ID dan Class Selector)
Menggunakan ID Selector (#intro, #intro h1) dan Class Selector (.button) pada file style_eksternal.css untuk memberikan gaya spesifik pada elemen kontainer utama dan tombol tautan.
<img width="1920" height="1080" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/27fd5169-ff9f-4403-8e18-d590c872a021" />

Pertanyaan dan Tugas
1.	Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS.
Eksperimen dilakukan dengan memindahkan letak teks Hello World agar berada di tengah halaman dan menambahkan efek hover pada tag <a> yang memiliki class .button.
<img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/ae61721b-64bf-410f-89bd-fbf6dd9241a8" />

2.	Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}?
Jawaban:
h1 {...} adalah Element Selector yang menerapkan aturan gaya ke seluruh tag h1 di dalam dokumen HTML.
#intro h1 {...} adalah Descendant / Combined Selector yang hanya menerapkan aturan gaya pada tag h1 di dalam elemen dengan ID intro. Selector ini memiliki tingkat spesifisitas lebih tinggi dibandingkan element selector biasa.

3.	Jika ada deklarasi CSS internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama, deklarasi manakah yang ditampilkan?
Jawaban: Inline CSS diprioritaskan dibandingkan aturan CSS internal maupun eksternal karena ditulis langsung pada elemen tersebut.
<img width="1920" height="1080" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/7e651602-941c-42d3-a8f6-216300b218a7" />

4.	Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector memiliki deklarasi CSS, deklarasi manakah yang ditampilkan?
Contoh elemen: <p id="deklarasi-id" class="deklarasi-class">
Jawaban: Deklarasi dari ID Selector lebih diprioritaskan dibandingkan Class Selector karena ID memiliki tingkat spesifisitas (specificity weight) yang lebih tinggi daripada Class dalam hierarki CSS.
<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/38006666-8825-4f35-a08f-8a42a441dfd6" />
