---
description: Log perubahan untuk semua versi Senjata + Busana Melayu - CIT Pack
icon: scroll
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# Log Perubahan

## Release 3.1 (8/6/2025) \[Java 1.12.2, 1.20.1-1.20.4, 1.21-1.21.1]

* Pilihan nama untuk bahasa Indonesia telah ditambahkan ke dalam CIT
  * Hanya untuk item yang namanya berbeza dengan nama dalam bahasa Melayu (Tengkuluk bukannya Tengkolok, Celana Melayu bukannya Seluar Melayu...)
* Fail penghargaan telah dikemas kini

## Release 3 (15/2/2025) \[Java 1.12, 1.20 - 1.20.4, 1.21-1.21.1]

* Kandungan pek telah diperkecilkan, untuk mengurangkan saiz fail
  * Removed all duplicate texture files, now they're all in the same place for both language options
  * Semua fail tekstur pendua telah dialih keluar, kini semuanya berada di tempat yang sama untuk kedua-dua pilihan bahasa
  * Nama setiap CIT untuk kedua-dua bahasa kini disimpan di dalam satu fail properties sahaja menggunakan regex, dan bukannya menggunakan dua fail berasingan
* Sokongan untuk nama Jawi pada semua CIT ditambah
  * CIT Kain Sarung menerima kedua-dua jenis hamzah, hamzah setara (کا`ء`ين ساروڠ), dan juga hamzah tinggi kazakh (کا`ٴ`ين ساروڠ) yang akan ditunjukkan sebagai hamzah tiga suku di dalam permainan dalam versi 1.20 dan ke atas
* Sokongan untuk mod Chime ditambah
  * Nama Jawi belum lagi disokong ketika menggunakan Chime
* Menamakan semula `Baju` kepada `Baju Melayu` dan `Seluar` kepada `Seluar Melayu` untuk semua set bahasa; serta `Machete` kepada `Parang` untuk nama bahasa Inggeris
  * Semasa mengemas kini pek, pastikan anda menamakan semula mana-mana item sedia ada yang menggunakan nama lama kepada yang baharu
* Pepijat di mana semua tekstur ikon Kain Sarung ditetapkan secara tidak sengaja kepada tekstur ikon Kasut untuk nama bahasa Melayu telah diperbaiki
* Pepijat di mana semua ikon Kasut masih dipaparkan dengan tekstur but vanila akibat pepijat di atas telah diperbaiki
* Fail penghargaan ditambah ke dalam fail zip
* Ikon pek telah dikecilkan daripada 1080x1080 kepada 512x512 untuk mengurangkan saiz fail

## Release 2 (31/8/2024) \[Java 1.12, 1.20 - 1.20.4, 1.21-1.21.1]

* \[SM] Tekstur keris diubah
  * Tekstur keris lama kini boleh didapati di bawah nama berikut: \[Material] Old Keris / Keris Lama \[Bahan]
* \[SM] Tekstur parang diubah untuk mengeluarkan tompokan emas pada pemegang
* \[BM] Tekstur tengkolok berlian diubah untuk menjadikan peralihan antara berlian dan netherit lebih "seamless"
* \[BM] Varian Busana Melayu perempuan ditambah (di bawah jenis Busana (P) dalam [jadual nama item](../../english/senjata-+-busana-melayu-cit-pack/item-table.md))
  * Ini serasi dengan pelaksanaan pek Busana Melayu asal
* Untuk nama bahasa Inggeris, nama yang digunakan untuk mendapatkan tekstur Baju lelaki telah ditukar daripada "\[Material] Baju" kepada "\[Material] Baju Melayu"
  * Ini adalah untuk menyelesaikan konflik antara nama CIT ini dan nama CIT "\[Material] Baju Kurung" yang digunakan oleh varian busana perempuan
* Isu ikon item kulit yang tidak muncul telah diperbaiki
* Fail penghargaan telah ditambahkan ke dalam fail zip
* Pek dikemas kini untuk menyokong 1.21
  * ~~Walau bagaimanapun, pek ini tidak akan berfungsi sama sekali pada versi selepas 1.20.4, disebabkan oleh~~ [~~kemas kini 1.20.5 yang merosakkan sistem CIT semasa~~](https://github.com/sp614x/optifine/issues/7658) Kini berfungsi pada versi 1.21.x melalui [OptiFine 1.21(.1)\_HD\_U\_J1\_pre9](https://optifine.net/downloads) atau [CIT Resewn v1.2.0](https://modrinth.com/mod/cit-resewn/changelog)
* Pek ikon telah dikemas kini

## Release 1 (29/4/2024) \[Java 1.12, 1.20 - 1.20.4]

* Terbitan pertama
* Mungkin berfungsi pada versi lain, tetapi ini belum diuji lagi

### Masalah yang diketahui

* Ikon item songkok tidak muncul sama sekali, tetapi model zirah masih berfungsi seperti yang dimaksudkan
