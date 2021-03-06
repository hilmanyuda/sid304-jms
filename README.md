# sid304-jms
Aplikasi ini adalah Sistem Informasi Desa CRI 3.04 yang disesuaikan untuk keperluan JMS.

Tujuan penyesuaian SID CRI ini adalah untuk:
- memudahkan JMS dalam melakukan pendampingan pada desa di lingkungan JMS untuk menerapkan SID
- tetap konsisten dengan release SID CRI, supaya bisa senantiasa mengadopsi update dari CRI. Untuk itu, penyesuaian yang dilakukan diusahakan membuat perubahan yang se-minim mungkin

Penyesuaian SID CRI ini dikelola di github untuk:
- merekam semua perubahan yg dibuat dari versi asli yg diperoleh dari Andi Anwar (30 Mei 2016)
- memungkinkan kembali ke revisi sebelumnya, apabila diperlukan
- memudahkan kolaborasi antar tim JMS dan juga dengan desa dampingan dalam mengembangkan SID
- backup online source code SID yg dapat diaskses setiap saat

Wiki sid304-jms (https://github.com/eddieridwan/sid304-jms/wiki) akan dikembangkan sesuai kebutuhan.

Catatan:
- sistem ini dikelola dengan merujuk pada lisensi GNU GENERAL PUBLIC LICENSE Version 3 (http://www.gnu.org/licenses/gpl.html)
- pengembang dan pemegang hak cipta aslinya adalah Combine Resource Institution (http://lumbungkomunitas.net/)
- SID 3.04 CRI terakhir yang telah digabung dengan sid304-jms di-share oleh Andi Anwar pada 30 Mei 2016
- sid304-jms akan terus menggabung versi baru yang mungkin sewaktu-waktu direlease oleh CRI melalui portal mereka di http://sid.web.id.

Di mana perubahan dilakukan/diperlukan untuk mengatasi suatu permasalahan atau memenuhi suatu permintaan,
kami akan usahakan untuk merekam masalahnya dan permintaannya di https://github.com/eddieridwan/sid304-jms/issues.

## SID Inti v SID Desa
Repository ini mempunyai dua cabang (git branch):
- cabang _master_, yang mengembangkan aplikasi sid304-jms inti, untuk di-release ke desa dampingan
- cabang _desa_, yang mengembangkan contoh penerapan sid304-jms di desa

Salah satu tujuan utama pengembangan sid304-jms adalah untuk memisahkan file SID inti dari file yang telah disesuaikan untuk keperluan desa. Pemisahan ini dimaksudkan untuk memudahkan upgrade SID di desa setiap kali ada release SID inti yang baru.

## Demo
Demo aplikasi SID 3.04-JMS dapat dilihat di http://sid.bangundesa.info. Kami usahakan agar versi yang terlihat di demo itu sesuai dengan status release terakhir repository ini. Demo itu menampilkan aplikasi desa yang dikembangkan di cabang _desa_.

Modul administrasi SID 3.04-JMS dapat diaskses pada http://sid.bangundesa.info/index.php/siteman. Masukkan Username = admin dan Password = sid304.
