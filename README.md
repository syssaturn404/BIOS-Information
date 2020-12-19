<h2><a id="user-content-octocat-fork-and-eight_pointed_black_star-star-this-repo" class="anchor" aria-hidden="true" href="https://github.com/syssaturn404/CLanguage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><img class="emoji" title="Design By Syssaturn404" alt="design-by-syssaturn404" src="https://github.githubassets.com/images/icons/emoji/octocat.png" height="20" width="20" align="absmiddle"> Syssaturn404 Repo <g-emoji class="g-emoji" alias="eight_pointed_black_star" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2734.png">💫</g-emoji></h2>
<p align="center">
  
![Bios-Information](https://www.if-koubou.com/img/images_3/what-does-a-pcs-bios-do-and-when-should-i-use-it.jpg)
```
>> Apa Itu BIOS ?

BIOS merupakan singkatan dari Basic Output System.
Sedangkan untuk pengertian mudahnya, ini merupakan sebuah sistem dasar bawaan komponen komputer
yang mana berfungsi untuk melakukan pengaturan-pengaturan basic pada sistem.
BIOS tentu saja bisa dibilang sangat penting perannya, karena mampu melakukan hal-hal seperti:

* Mengubah boot ketika ingin install ulang.
* Melihat spesifikasi komputer atau laptop.
* Melihat detail informasi komponen.
* Mengatur frekuensi komponen.
* Dan lain-lain.

>> Cara Mengecek Versi BIOS dengan Mudah
Lantas, bagaimana sih cara mengetahui versi BIOS ?

Di sini akan dibahas beberapa cara termudah yang bisa Anda coba. 
Cara-cara ini pun tentu saja bisa diterapkan di semua merk komputer atau laptop, 

seperti:

* ASUS.
* Acer.
* Lenovo.
* HP.
* Dell.
* Dan lain-lain.
```
```
>> Melalui DXDIAG

Caranya klik tombol Windows + R ==> ketik “dxdiag“ ==> kemudian klik OK. 
Periksa pada kolom BIOS untuk mengetahui versi BIOS.
Bisa juga apabila kalian ingin menyimpan informasi tersebut ke dalam
komputer anda dengan cara klik save all information.
Cara ini bisa diterapkan di semua versi Windows. 
Dari hasil tes saya sendiri, mulai dari Windows XP, Windows Vista, Windows 7, Windows 8, sampai Windows 10.
FYI, selain untuk mengetahui versi BIOS, kita juga bisa melihat informasi
spesifikasi dasar yang masih berkaitan dengan komponen.
Misalnya tipe VGA, jumlah memori (RAM), sampai prosesor yang dipakai. 
Silakan explore sendiri saja selebihnya.

>> Dengan System Information

Sebenarnya, System Information lebih umum digunakan untuk mengetahui 
informasi-informasi berterkaitan dengan hardware secara detail. 
Tapi saking lengkapnya informasi yang bisa didapatkan, kita juga bisa melihat versi BIOS di sana.

Untuk caranya mudah:

Pertama ==> buka Windows Run, sama seperti sebelumnya (kombinasi tombol Windows + R).
Lalu ketik “msinfo32” dan klik OK.
Buka/masuk ke menu System Summary.
Kemudian cek pada kolom BIOS version/Date, di sana akan tampil versi BIOS.
Melalui System Information ini, kita juga bisa mengetahui mode BIOS yang dipakai (UEFI, AHCI)
informasi boot, SMBIOS (System Management BIOS) dan lain-lain.
Sama seperti DXDIAG, coba deh explore sendiri.

>> Menggunakan CMD(Command Prompt)

Untuk menggunakan langkah-langkah ini, silakan klik Start pada taskbar Windows ==>
Pada kolom pencarian ==> ketik “CMD“, lalu buka hasilnya.
Atau langkah alternatifnya, bisa coba klik tombol Windows + R ==> Ketik “CMD” ==> Lalu klik OK.
Setelah Command Prompt terbuka, silakan masukkan perintah “bios wmic get smbiosbiosversion.”
Di sana akan muncul nomor versi BIOS atau Firmware UEFI dari komputer/laptop yang dipakai.
Karena CMD merupakan fitur bawaan, cara ini bisa diterapkan di semua versi Windows. 
Namun untuk beberapa kondisi, terkadang perintah yang dimasukkan tidak aktif.
Maka dari itu dicoba dulu.

>> Melalui REGEDIT(Registy Editor)

Nggak banyak orang yang mau membuka regedit.
Bukan tanpa alasan, karena memang di regedit ini banyak pengaturan-pengaturan yang 
lebih kurangnya bisa memicu error sistem, utamanya kalau nggak ter-setting dengan benar.
Tapi khusus yang ini, untuk sekedar memeriksa versi BIOS lewat regedit saja sih aman, kok.
Coba ikuti langkah-langkahnya, supaya nggak salah.
Caranya, buka Windows Run ==> Ketik “regedit” ==> Lalu buka/klik OK.
Setelah itu, masuk ke menu HKEY_LOCAL_MACHINE\HARDWARE\DESCRIPTION\SYSTEM.
Di sana akan tertera informasi BIOS pada reg SystemBiosVersion.
Selain itu, terdapat juga informasi terkait pada key registy lainnya. 
Misalnya boot architecture, component information, dan sejenisnya.
Mungkin ada artikel lain yang menyampaikan lebih dari ini
ini hanya untuk pengetahuan, siapa tau suatu saat anda membutuhkan informasi ini
akan sangat berguna ^-^
```
