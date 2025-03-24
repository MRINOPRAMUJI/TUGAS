Soal :
1. Jelaskan Struktur antar Hubungan dan beri contohnya .
2. Bila Terlalu banyak modul atau perangkat dihubungkan pada bus maka akan terjadi penurunan kinerja, Sebutkan Penyebabnya ?
3. Umumnya perangkat berprioritas paling rendah memiliki waktu tunggu rata-rata yang paling singkat. Dengan dasar ini biasanya CPU diberi perioritas tertinggi pada SBI. Sebutkan alasan perangkat berprioritas 16 
   memiliki waktu tunggu rata-rata paling rendah ? Di bawah kondisi Seperti apa keadaan diatas tidak berlaku ?

Jawaban : 
1. Dalam dunia komputer, struktur antar hubungan dapat merujuk pada cara berbagai perangkat keras dan perangkat lunak saling berhubungan melalui jalur komunikasi,contoh nya bus. Bus adalah sebuah subsistem yang berfungsi untuk mentransfer data atau daya antara komponen dalam sebuah komputer atau antar komputer. Dalam sistem komputer, bus termasuk perangkat internal yang memungkinkan pengiriman informasi dengan kecepatan tinggi.

Contoh Bus:
PCI (Peripheral Component Interconnect)
PCI adalah jenis bus yang dirancang untuk menghubungkan berbagai perangkat keras dengan bandwidth tinggi. Bus ini bersifat prosesor-independen, sehingga dapat digunakan sebagai bus mezzanine maupun bus periferal. Standar PCI dikembangkan oleh PCI Special Interest Group, sebuah konsorsium yang dibentuk oleh Intel Corporation dan beberapa perusahaan lainnya pada tahun 1992. PCI diciptakan sebagai solusi untuk menggantikan bus ISA/EISA yang sebelumnya digunakan pada komputer IBM PC dan kompatibelnya.

USB (Universal Serial Bus)
USB adalah teknologi yang memungkinkan perangkat eksternal seperti printer, scanner, keyboard, mouse, flash drive, dan kamera digital terhubung ke komputer dengan lebih mudah. USB mendukung kecepatan transfer data hingga 12 Mbps dan kini menjadi standar umum dalam komputer modern. Sebagian besar PC saat ini telah dilengkapi dengan minimal dua port USB. Dibandingkan dengan parallel port dan serial port, USB lebih praktis dan fleksibel dalam penggunaannya.

BUS PCI
PCI merupakan bus yang tidak bergantung pada prosesor dan berfungsi sebagai bus mezzanine atau bus periferal. Standar PCI memiliki 64 jalur data dengan kecepatan 33 MHz serta mampu mentransfer data hingga 263 MB per detik atau sekitar 2,112 Gbps. Selain memiliki kecepatan yang tinggi, PCI juga lebih ekonomis karena hanya membutuhkan sedikit komponen.

BUS ISA (Industry Standard Architecture)
Bus ISA dikembangkan sebagai standar yang kompatibel dengan perangkat sebelumnya. Pada dasarnya, bus ini merupakan pengembangan dari bus PC/AT yang bekerja pada kecepatan 8,33 MHz. Salah satu kelebihan dari bus ISA adalah kompatibilitasnya dengan perangkat keras lama, memungkinkan penggunaan kartu ekspansi dan mesin yang lebih tua tanpa mengalami kendala.

2. Habisnya kapasitas transfer bus.
Setiap bus memiliki lebar jalur data yang berbeda-beda. Jika jumlah data yang ditransfer melebihi kapasitas maksimum bus, maka akan terjadi penurunan kecepatan transfer, menyebabkan keterlambatan dalam pengiriman data.

Antrian penggunaan bus semakin panjang.
Semakin banyak perangkat yang menggunakan bus secara bersamaan, semakin panjang antrian data yang harus diproses. Hal ini dapat memperlambat proses transfer data karena setiap perangkat harus menunggu giliran untuk menggunakan bus.

Semakin besar delay propagasi dalam koordinasi penggunaan bus.
Delay propagasi terjadi ketika sistem harus mengatur penggunaan bus di antara berbagai perangkat. Semakin banyak perangkat yang terhubung, semakin lama waktu yang dibutuhkan untuk mengkoordinasikan akses ke bus, sehingga memperlambat komunikasi data.

Terjadinya konflik akses bus.
Jika beberapa perangkat mencoba mengakses bus secara bersamaan tanpa mekanisme pengaturan yang efektif, maka dapat terjadi konflik yang mengakibatkan penurunan performa atau bahkan kegagalan transfer data.

Kinerja bus bergantung pada frekuensi clock.
Kecepatan transfer data pada bus dipengaruhi oleh frekuensi clock yang digunakan. Jika frekuensi clock rendah, maka kecepatan komunikasi antar komponen juga akan lebih lambat dibandingkan dengan bus yang memiliki frekuensi lebih tinggi.

Jenis arsitektur bus yang digunakan.
Arsitektur bus yang lebih lama, seperti ISA, memiliki kecepatan yang jauh lebih rendah dibandingkan dengan standar yang lebih baru seperti PCIe. Pemilihan jenis bus yang sesuai dengan kebutuhan sangat penting untuk mengoptimalkan performa sistem.

3. Bus Data adalah jalur komunikasi yang digunakan untuk mentransfer data antara berbagai komponen dalam sistem komputer. Bus ini terdiri dari 8, 16, 32, atau lebih jalur sinyal paralel yang memungkinkan pengiriman data dengan lebih cepat. Jalur data bersifat dua arah (bidirectional), sehingga CPU dapat membaca maupun mengirim data ke memori atau port.

Dalam sebuah sistem, banyak perangkat yang terhubung ke bus data, namun hanya satu perangkat yang dapat menggunakannya pada satu waktu. Untuk mengelola penggunaan bus ini, setiap perangkat harus memiliki tiga keadaan (tristate), sehingga dapat dikontrol dan dihubungkan ke bus data tanpa menyebabkan konflik dalam transfer data.
