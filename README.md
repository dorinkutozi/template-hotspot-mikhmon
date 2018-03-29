# template-hotspot-mkhmon
Template login hotspot Mikrotik, cocok dipasangkan dengan [Mikhmon](https://laksa19.github.io)

## Download
[Download Template](https://github.com/laksa19/template-hotspot-mikhmon/archive/master.zip)

## Lisensi
Template ini gratis, silahkan edit yang perlu disesuaikan. Jangan menghilangkan atau merubah bagian footer (Powered by Mikhmon)!
## Yang perlu disesuaikan
### hotspot2
1. Daftar paket wifi disesuaikan di file (paket-wifi.csv) dengan text-editor.
2. Logo dapat diganti dengan format (logo.png dan sponsor.png) ditaruh di folder img.
3. Sesuaikan juga yang dirasa perluu disesuaikan (nama usaha alamat dll).
### hotspot3 & hotspot4
1. Daftar paket wifi disesuaikan di file (paket-wifi.csv) dengan text-editor.
2. Logo dapat diganti dengan format (logo.png dan sponsor.png) ditaruh di folder img.
3. Nama usaha, alamat, notifkasi expired dan lainnya di (data.js).

      Contoh : 
      ```
      Tambahakan tag <br> untuk membuat baris baru.
      {"nama" : "Kemangi 41"} menjadi {"nama" : "Hotspot Murah"}
      {"notifikasi" : "Mohon maaf internet Telkom dalam perbaikan."} menjadi {"notifikasi" : ""}
      {"expired" : "Mohon maaf Kode Voucher atau User yang Anda masukkan sudah expired. <br><br> Silahkan gunakan Kode Voucher yang masih berlaku,<br> atau lakukan pembayaran untuk mengaktifkan user kembali. <br> Terima Kasih."}
      ```
4. Template tidak menggunakan notifikasi expired di laman terpisah, melainkan menggunakan [modal](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_modal) sudah terintegrasi di login.html.

