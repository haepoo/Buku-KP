# Buku Kerja Praktik
Buku Kerja Praktik ini ditulis menggunakan LaTeX.

---
## Definisi
LaTeX adalah bahasa markup dokumen atau sistem penyiapan teks untuk membuat sebuah dokumen. LaTeX memungkinkan penggunanya melakukan *typesetting* dan mencetak hasil kerjanya dalam bentuk tipografi yang baik. LaTeX sangat cocok digunakan untuk membuat dokumen yang membutuhkan banyak pemformatan, seperti artikel ilmiah atau teknis, *paper*, laporan, tugas akhir, buku yang mengandung banyak rumus matematika atau *script* dan *code* program, serta skripsi, *thesis*, dan disertasi.

**Kelebihan LaTeX:**
* Hasil tampilan dokumen sangat rapi dan profesional
* Tidak perlu memikirkan *layout* Ketika mengetik karena *layout* telah diatur oleh file utama (misal: main.tex).
* *Free*! Sedangkan MS Word berbayar
* Cocok digunakan untuk menulis rumus matematika serta *script* dan *code* program karena pengaturannya mudah
* Cocok untuk *programmer*
* Tidak pernah *crash*
* *File*-nya relatif kecil
* Tutorial dan dokumentasi *command*-nya banyak dan mudah dicari di internet

**Kekurangan LaTeX:**
* Perlu kesabaran dan ketekunan karena tidak se-*user-friendly* MS Word
* Jika dokumennya pendek, terlalu berlebihan jika menggunakan LaTeX 
* Harus hafal *command* supaya lebih cepat dalam mengetik

---
## Instalasi

1. Buka terminal
2. Install Tex Live
```
sudo apt-get update
sudo apt-get install texlive-full
```
3. Install Tex Studio
```
sudo apt-get install texstudio
```
4. Install Windows Fonts
```
sudo apt-get install ttf-mscorefonts-installer
sudo fc-cache -f -v
```
5. Buka Tex Studio yang telah terinstall
6. Buka menu `Option`, pilih `Configure Texstudio...`
7. Pada tab `build`, pilih `xelatex` sebagai *default compiler*
8. Pada tab `command`, tuliskan `xelatex -synctex=1 -interaction=nonstopmode --shell-escape %.tex` sebagai *xelatex command*
9. Install python-pygments
```
sudo apt-get install python-pygments
```
10. Gunakan `build & view` atau F5 untuk meng-*compile*

Selamat membaca buku KP kami!
