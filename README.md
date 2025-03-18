
# Hangman Game

Hangman adalah permainan tebak kata sederhana di mana pemain harus menebak kata yang tersembunyi dengan menebak huruf-hurufnya. Setiap tebakan yang salah akan menambah bagian tubuh hangman. Pemain harus menebak kata sebelum hangman terbentuk sepenuhnya.

## Preview Game

Berikut adalah tampilan dari game Hangman:

![Screenshot 2025-03-18 084617](https://github.com/user-attachments/assets/ff390eba-8e75-419d-bff8-d77bc02df2da)

## Demo Game

Anda dapat mencoba game ini secara langsung di:  
👉 [Demo Hangman Game](https://faajharr.github.io/hangman-game/)

## Cara Bermain

1. Buka file `index.html` di browser Anda atau kunjungi [Demo Game](https://faajharr.github.io/hangman-game/).
2. Anda akan melihat kata yang harus ditebak ditampilkan sebagai garis bawah (misalnya: `_ _ _ _ _`).
3. Gunakan keyboard virtual di layar untuk menebak huruf.
4. Jika huruf yang ditebak benar, huruf tersebut akan muncul di kata yang harus ditebak.
5. Jika huruf yang ditebak salah, bagian tubuh hangman akan ditambahkan.
6. Anda memiliki 6 kesempatan untuk menebak huruf yang salah sebelum hangman terbentuk sepenuhnya.
7. Jika Anda berhasil menebak kata sebelum hangman terbentuk, Anda menang!
8. Jika hangman terbentuk sepenuhnya sebelum kata berhasil ditebak, Anda kalah.

## Pertanyaan Sederhana

Berikut adalah beberapa contoh pertanyaan sederhana yang digunakan dalam permainan:

- **Pertanyaan**: Buah merah atau hijau yang sering dimakan segar.  
  **Jawaban**: Apel

- **Pertanyaan**: Hewan peliharaan yang suka mengeong.  
  **Jawaban**: Kucing

- **Pertanyaan**: Alat musik berdawai yang dimainkan dengan dipetik.  
  **Jawaban**: Gitar

- **Pertanyaan**: Benda bulat yang digunakan dalam berbagai olahraga.  
  **Jawaban**: Bola

- **Pertanyaan**: Makanan manis yang terbuat dari biji kakao.  
  **Jawaban**: Cokelat

## Fitur

- **Tampilan Responsif**: Game dapat dimainkan di berbagai perangkat, termasuk desktop dan mobile.
- **Keyboard Virtual**: Memudahkan pemain untuk menebak huruf tanpa menggunakan keyboard fisik.
- **Petunjuk**: Setiap kata memiliki petunjuk untuk membantu pemain menebak.
- **Animasi Hangman**: Visualisasi hangman yang muncul secara bertahap saat pemain melakukan kesalahan.

## Struktur File

- `index.html`: File utama yang berisi struktur HTML untuk game.
- `style.css`: File CSS untuk mengatur tampilan dan gaya game.
- `scripts/word-list.js`: File JavaScript yang berisi daftar kata dan petunjuk.
- `scripts/script.js`: File JavaScript yang berisi logika utama game.

## Cara Menjalankan

1. Clone repository ini atau download file ZIP.
2. Buka folder proyek di komputer Anda.
3. Buka file `index.html` di browser Anda.
4. Mulai bermain!

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan buka *issue* atau ajukan *pull request*. Semua kontribusi sangat diterima!

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

### Catatan
- Pastikan untuk mengganti `#` pada atribut `src` di file `index.html` dengan path gambar yang sesuai jika Anda ingin menambahkan gambar hangman atau animasi GIF.
- Anda juga dapat menambahkan lebih banyak kata dan petunjuk di file `word-list.js`.

Semoga bermanfaat! 😊
