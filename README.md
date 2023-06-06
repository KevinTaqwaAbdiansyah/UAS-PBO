# Penjelasan Source Code

Anggota Kelompok :

1.Zahrah Hafizah Fakhri (G1A022046)
2.Neli Agustin (G1A022048)
3.Kevin Taqwa Abdiansyah (G1A022078)

Membuat Game Hangman. 

Penjelasan Kode Secara Singkat

Kode pertama mengimpor beberapa modul yang diperlukan, termasuk modul random, time, dan pygame. Selanjutnya, beberapa variabel warna dan ukuran layar didefinisikan. Daftar kata-kata yang akan ditebak juga telah disediakan. Kemudian, layar permainan dibuat menggunakan fungsi pygame.display.set_mode(). Gambar-gambar untuk permainan hangman dimuat ke dalam daftar hangman_images. Suara tebakan benar dan salah juga dimuat menggunakan pygame.mixer.Sound().

Ada beberapa fungsi yang didefinisikan, seperti draw_text() untuk menggambar teks di layar dan draw_hangman() untuk menggambar gambar hangman. Fungsi utama hangman() mengimplementasikan logika permainan. Kata yang akan ditebak dipilih secara acak, dan pemain diberikan kesempatan untuk menebak huruf-hurufnya. Saat pemain menebak huruf dengan benar, huruf tersebut ditampilkan di tempat yang sesuai dalam kata yang harus ditebak. Jika pemain menebak huruf-huruf dengan benar dan berhasil menebak seluruh kata sebelum kesempatan habis, pemain menang. Jika pemain gagal menebak kata sebelum kesempatan habis, pemain kalah.

Setelah permainan selesai, pesan "YOU WIN!" atau "YOU LOSE!" ditampilkan selama beberapa detik sebelum program keluar. Terakhir, permainan dimulai dengan memanggil fungsi hangman(), dan ketika permainan selesai, modul Pygame ditutup dengan pygame.quit().

Tampilan awal game
![IMG-20230606-WA0019](https://github.com/KevinTaqwaAbdiansyah/UAS-PBO/assets/129782065/8108bd26-3b77-4b12-a77c-d8ded410e7d9)

Tampilan ketika game mulai dijalankan
![IMG-20230606-WA0018](https://github.com/KevinTaqwaAbdiansyah/UAS-PBO/assets/129782065/220d9f37-0028-44c9-94d8-0b15ed146fcc)
![IMG-20230606-WA0020](https://github.com/KevinTaqwaAbdiansyah/UAS-PBO/assets/129782065/dfc711d7-c788-49d1-8708-21a45093257f)

Tampilan ketika kata berhasil di tebak
![IMG-20230606-WA0017](https://github.com/KevinTaqwaAbdiansyah/UAS-PBO/assets/129782065/fd3ff3d7-5317-42ba-afde-3c9670a7817c)

Tampilan ketika kata tidak berhasil di tebak
![IMG-20230606-WA0023](https://github.com/KevinTaqwaAbdiansyah/UAS-PBO/assets/129782065/8329d815-f3e4-48d8-8b34-a7693e55f2e8)

