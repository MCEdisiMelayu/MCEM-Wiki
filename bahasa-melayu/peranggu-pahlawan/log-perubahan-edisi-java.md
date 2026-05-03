---
description: Log perubahan untuk semua versi Peranggu Pahlawan (Edisi Java)
icon: scroll
layout:
  width: wide
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
  metadata:
    visible: true
  tags:
    visible: true
---

# Log Perubahan (Edisi Java)

## v1.4.0 (1/5/2026) \[Fabric & Quilt 1.20.1/1.21.1/1.21.4-1.21.11/26.1, Forge 1.20.1, NeoForge 1.21.1]

### Penambahan

* Mod telah dikemas kini ke versi 26.1 (Tiny Takeover) bersama dua versi hotfixnya, 26.1.1 dan 26.1.2 untuk pemuat mod Fabrik dan Quilt
  * Versi 26.1 akan menerima kemas kini tampalan sebaik sahaja versi Sinytra Connector untuk 26.1 tersedia
  * Sokongan untuk model zirah baharu untuk makhluk kecil (baby mob) telah ditambah
    * Isu yang Diketahui: Samping dan kasut tidak akan kelihatan apabila dipakai oleh makhluk kecil. Ini disebabkan oleh cara tekstur dipetakan kepada model zirah, yang menjadikannya mustahil untuk memuatkan bentuk samping dan kasut
* \[ALL] Sokongan Legacy4J telah ditambah!
  * Mod ini kini menyokong antara muka pertukangan seperti Legacy Console Edition!
  * Tab kreatif telah diubah agar lebih sesuai dengan antara muka 10 item setiap baris dalam L4J (bukannya antara muka 9 item setiap baris vanilla)
    * Perubahan ini hanya akan terpakai apabila menggunakan mod Legacy4J
* \[ALL] Sokongan Combatify telah ditambah!

### Perubahan

* \[26.1] Dagangan penduduk kampung telah dipindahkan daripada kod Fabric kepada sistem data-driven
* \[26.1] Resipi pewarnaan busana kulit telah dikemas kini kepada sistem baharu
* \[ALL] Beberapa piksel tambahan pada tekstur model Kasut Tembaga telah dipadamkan, kerana ia akan kelihatan tidak kena bila anda hanya memakai Kasut Tembaga
* \[ALL] Alias dalam bahagian penghargaan fabric.mod.json dan (neoforge.)mods.toml telah dikemas kini

### Pembaikan

* \[1.21.1] Beberapa nilai ketahanan zirah dan ketahanan tolakan
* Busana Rantai kini tidak lagi mempunyai +2 ketahanan zirah
* Busana Netherit kini tidak lagi terlalu overpowered, kini mempunyai +1 ketahanan tolakan seperti zirah netherit vanila dan bukannya **+10** (disebabkan oleh salah taip dalam kod: 0.1F vs 1.0F)

## v1.3.0 (12/12/2025) \[Fabric & Quilt 1.20.1/1.21.1/1.21.4-1.21.11, Forge 1.20.1, NeoForge 1.21.1]

#### Penambahan

* Mod ini telah dibawa ke versi 1.21.9 (The Copper Age) dan versi hotfixnya (1.21.10) untuk pemuat mod Fabric dan Quilt
* Mod ini telah dibawa ke versi 1.21.11 (Mounts of Mayhem) untuk pemuat mod Fabric dan Quilt
* Keris, Parang dan Busana Tembaga!
  * Mempunyai statistik yang hampir sama dengan vanilla counterpart mereka, selain daripada perbezaan yang disenaraikan dalam halaman mod di Modrinth
  * Penambahan tembaga ini telah dibawa ke semua versi yang disokong mod ini, dengan beberapa peringatan:
    * Item-item tembaga ini **tidak boleh diperoleh dalam mod kemandirian**, dan buat masa sekarang hanya tersedia dalam mod kreatif
    * Pemakaian zirah tembaga menggunakan suara yang sama seperti memakai zirah besi
    * Tag item `copper_tool_materials` telah dibawa ke semua versi yang disokong mod ini
* Terjemahan Bahasa Indonesia Ejaan Lama (Bahasa Indonesia edjaän lama) telah ditambah
  * Terima kasih Dustin945 untuk terjemahannya (dan penambahan bahasa in ke Minecraft!)
* \[1.21.1] Sokongan Epic Fight untuk NeoForge 1.21.1 telah ditambah

#### Perubahan

* Fail tag item `head_armor`, `chest_armor`, `leg_armor` dan `foot_armor` telah dipindahkan ke sub-direktori teratas `tag/item` daripada `tag/item/enchantable`
  * Fail tag item `durability` dan `equippable` telah dialih keluar, kerana ia kini tidak diperlukan hasil daripada perubahan di atas, tetapi tiada apa yang sepatutnya berubah dalam permainan
* Tengkolok dan gandik besi sudah tidak lagi berada dalam tier berlian untuk perlengkapan makhluk
* Set zirah emas kini boleh muncul semula pada makhluk (kedua-dua zirah vanila dan busana dalam mod ini)
* Kod perlengkapan makhluk telah diubah agar lebih sepadan dengan tingkah laku vanila

#### Resipi Pertukangan Busana Rantai

* Telah ditambahkan semula ke dalam mod, namun tidak dipaparkan di dalam buku resipi, dan pemasangan mod [Sumbaii999's Craftable Chainmail Armor](https://modrinth.com/datapack/craftable-chainmail-armor-by-sumbaii999/) adalah diperlukan untuk menukangnya dalam permainan
  * Agak kurang vanilla, tapi kalau korang nak pakai juga sekurang-kurangnya pilihan itu ada
  * Kalau korang nak buat Baju Melayu Rantai atau Seluar Melayu Rantai dalam versi-versi yang tidak disokong oleh mod Polymorph (1.21.4 dan ke atas), kesemua slot yang tinggal perlu diisi dengan Iron Nugget / Nuget Besi
    * Hal ini supaya dapat mengelak konflik resipi dengan resipi Zirah Dada Rantai dan Zirah Kaki Rantai (yang bentuknya sama dan juga tidak dipaparkan di dalam buku resipi)

## v1.2.1 (6/9/2025) \[Fabric & Quilt 1.20.1/1.21.1/1.21.4-1.21.8, Forge 1.20.1, NeoForge 1.21.1]

### Perubahan

* Masalah-masalah dengan fail bahasa yang berikut telah dibaiki
  * \[ALL] Typo yang sangat kecil dalam terjemahan bahasa Indonesia telah dibaiki
    * Terjemahan tersebut ialah Chainmail Gandik yang diterjemah sebagai "Gandi**l** Rantai"
  * \[1.21.8] Satu tanda koma yang tiada di dalam fail terjemahan bahasa Melayu telah ditambah semula. Kini terjemahan bahasa Melayu untuk keterangan kemajuan yang diubah suai telah berfungsi semula.
  * Jika anda terkesan oleh isu-isu (kecil) ini, anda mungkin mahu mengemas kini kepada versi ini.

### Catatan

**Versi ini serasi dengan pelayan yang menjalankan Peranggu Pahlawan v1.2.0** (pada pemuat mod Fabric/Quilt dan (Neo)Forge melalui Connector), kerana satu-satunya perkara yang diubah dalam versi ini ialah fail bahasa dan tiada satu pun kod yang diubah

## v1.2.0 (31/8/2025) \[Fabric & Quilt 1.20.1/1.21.1/1.21.4-1.21.8, Forge 1.20.1, NeoForge 1.21.1]

### Penambahan

* \[Fabric/Quilt] Mod ini kini telah di bawa ke versi-versi "game drop" selepas 1.21.1 untuk mod loader Fabric dan Quilt
  * The Garden Awakens (1.21.4)
  * Spring to Life (1.21.5)
  * Chase the Skies (1.21.6) dan kedua versi hotfix yang menyusul (1.21.7 dan 1.21.8)
  * Sila ambil perhatian bahawa tidak ada rancangan untuk membawa mod ini ke versi lebih tua daripada versi 1.20.1/1.21.1.
* \[1.21.1 NeoForge] Kunci terjemahan (translation key) untuk keterangan mod apabila menggunakan NeoForge tanpa mod Better ModList telah ditambah (terjemahan ini juga akan muncul apabila menggunakan mod Catalogue)
* \[1.20.1 & 1.21.1] Polymorph telah ditambah sebagai kebergantungan optional
* \[ALL] Semua item dalam mod ini telah disepadukan sepenuhnya ke dalam gameplay vanila berikut
  * Villager Leatherworker dan Armorer kini boleh menjual kepingan busana
  * Villager Weaponsmith and Toolsmith Villagers can now sell keris and parang
  * Zombie, Skeleton, Husk dan Stray kini boleh menjelma sambil memakai busana
  * Zombie, Husk dan Vex kini boleh menjelma dengan keris besi
  * Vindicator kini boleh menjelma dengan parang besi
  * Piglin kini boleh menjelma dengan keris dan busana emas
  * Zombified Piglin kini boleh menjelma dengan keris emas
  * Piglin Brute kini boleh menjelma dengan parang emas
* \[ALL] Semua item emas dalam mod ini telah ditambahkan ke dalam tag `piglin_loved`

### Penghapusan

* Resipi pertukangan untuk busana rantai telah dihapus, memandangkan ia kini boleh dijumpai dalam gameplay biasa

### Perubahan

* Tag item untuk kesemua 9 kepingan busana kini telah dipisahkan ke dalam tag mereka masing-masing, dan bukan dikumpulkan mengikut slot zirah yang digunakan
  * Tag yang lama masih ada, tapi diubah untuk merujuk kepada tag-tag yang baharu di atas
* Tag item `swords` dan `axes` masing-masing kini merujuk terus kepada tag item `keris` dan `parang`, dan bukan menyenaraikan ulang kesemua item dalam tag-tag tersebut
* Keperluan untuk kemajuan "Cover Me in Debris" ("Disarungi Puing") telah diubah supaya apabila pemain memiliki satu set penuh dengan mana-mana kombinasi daripada kedua set busana, kemajuan dapat diberikan, dan tidak memerlukan pemain mempunyai satu set penuh untuk satu jenis set busana

|                                                                                                                                                                                                         v1.1.0                                                                                                                                                                                                        |                                                                                                                                                                                                         v1.2.0                                                                                                                                                                                                        |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| ![](https://wsrv.nl/?url=https%3A%2F%2Fwww.gitbook.com%2Fcdn-cgi%2Fimage%2Fdpr%3D2%2Cwidth%3D1168%2Conerror%3Dredirect%2Cformat%3Dauto%2Fhttps%253A%252F%252Ffiles.gitbook.com%252Fv0%252Fb%252Fgitbook-x-prod.appspot.com%252Fo%252Fspaces%25252FTE5gKTpTSgEDzTm1dxrq%25252Fuploads%25252FRVOs3odBs2X4fSrwpgge%25252Fpp_v1.1.0_check.png%253Falt%253Dmedia%2526token%253D8ff61922-3c02-4b0c-aaa4-26ba5a4b2d76\&n=-1) | ![](https://wsrv.nl/?url=https%3A%2F%2Fwww.gitbook.com%2Fcdn-cgi%2Fimage%2Fdpr%3D2%2Cwidth%3D1168%2Conerror%3Dredirect%2Cformat%3Dauto%2Fhttps%253A%252F%252Ffiles.gitbook.com%252Fv0%252Fb%252Fgitbook-x-prod.appspot.com%252Fo%252Fspaces%25252FTE5gKTpTSgEDzTm1dxrq%25252Fuploads%25252FxbL67bhmYMcX2lHEd2xm%25252Fpp_v1.1.1_check.png%253Falt%253Dmedia%2526token%253Dc3f2c0b2-9a2f-450d-a619-9184bb220f20\&n=-1) |
|                                                                                                                                                         Hanya dua kombinasi teratas sahaja yang boleh memberikan kemajuan, iaitu satu untuk setiap set busana                                                                                                                                                         |                                                                                                                                                                             Mana-mana kombinasi kedua set busana boleh memberikan kemajuan                                                                                                                                                                            |

## v1.1.0 (8/6/2025) \[Fabric & Quilt 1.20.1/1.21.1, Forge 1.20.1, NeoForge 1.21.1]

### Penambahan

* Terjemahan bahasa Indonesia! Terima kasih Dustin945!
* Sokongan mod Sword Blocking Mechanics untuk Keris dan Parang!
* \[1.20.1] Sokongan mod Epic Fight untuk Keris dan Parang!
* \[1.21.1] Tag item `keris` dan `parang`&#x20;
* \[1.20.1] Penambahan semua tag item dari versi mod untuk 1.21.1

### Perubahan

* Parang kini mempunyai kebolehan istimewa! Ia kini boleh melombong kayu balak dalam kawasan 3x3
  * Kelajuan perlombongan parang kini telah dikurangkan dengan ketara untuk menjadikannya tidak terlalu op tanpa sihir Kecekapan/Efficiency
  *    Fungsi pemecahan blok 3x3 baharu hanya terpakai pada semua jenis batang kayu (sama ada yang biasa/balak, batang/hifa kirmizi dan gila, dan juga semua jenis batang kayu yang dikupas kulit), dan bukan sebarang blok kayu lain (papan, papak, tangga dll.)
* Beberapa perkara dalam fail bahasa telah diperbetulkan, termasuk ejaan `armour` dalam bahasa Inggeris British menggunakan ejaan Inggeris Amerika `armor`
* Kod jadual rampasan telah diubah supaya dua varian busana muncul dalam satu "call" dan bukannya dua "call" yang berasingan
  * Dengan itu peluang untuk setiap "call" juga telah digandakan
* Gandik kulit dalam peti rumah penduduk kampung tukang jahit kini sudah secara tidak sengaja dijana dengan sihir tahap tinggi
* modid Sinytra Connector yang ditakrifkan di dalam fail (`neoforge.`)`mods.toml` kini telah diubah daripada `connector` menjadi id tepatnya iaitu`connectormod`
* \[1.21.1] Kebergantungan Forge telah dibuang daripada fail `neoforge.mods.toml`
* Penghargaan telah dikemas kini

## v1.0 (3/2/2025) \[Fabric & Quilt 1.20.1/1.21.1, Forge 1.20.1, NeoForge 1.21.1]

* Terbitan pertama
