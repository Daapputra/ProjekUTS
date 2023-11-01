# Membuat game Survival dengan tampilan yang menghibur

## 1.1 Latar Belakang
Game ini merupakan game RPG (Role Playing Game). Sebelumnya apa yang disebut denga game RPG itu? Game RPG adalah game yang dimana pemain mengontrol satu karakter atau tokoh utama dalam sebuah game yang dimainkan, sebagai tokoh utama, pemain dapat menjelajah, berinteraksi, dan berperan penuh dalam game tersebut. Di sini saya memang suka dengan game yang bertemakan RPG atau survival karena saya suka dengan game yang bertemakan bertahan hidup, karena game seperti itu menurut saya tidak gampang membosankan karna ada banyak hal yang dapat di lakukan dari game bertemakan tersebut. Contoh nya seperti Undawn, Lifeafter, dan masih banyak lagi, game-game yang saya sebutkan tadi adalah game yang bertemakan RPG atau survival. Di game tersebut contoh nya kita dapat bertahan hidup dari berbagai serangan monster dan juga dapat mencari bahan-bahan untuk bertahan hidup seperti makanan atau pun alat untuk menyerang dan bertahan. 

Maka dari itu pada kesempatan kali ini saya ingin membuat game yang bertemakan RPG atau survival sesuai dengan game yang saya suka,tetapi ada perbedaan di game yang saya ingin buat ini karena di game yang saya akan buat ini, game survival nya itu tidak menyeramkan seperti game-game yang saya sebutkan di atas, karena terdapat beberapa orang yang ingin mencoba atau memainkan game survival tetapi tidak berani karena tampilan dan di dalam game nya itu menyeramkan karena realistis dari segi grafik nya, nah di sini saya akan menyediakan game survival tetapi dengan grafik yang menghibur dan penuh warna dan juga dari segi monster nya tidak begitu menyeramkan, jadi agar yang ingin mencoba game survival tetapi tidak berani karena takut akan tampilan di dalam in game yang menyeramkan teratasi dengan game yang saya buat ini.

Jadi di game ini kita dapat menjelajah map untuk berpetualang atau yang biasa kita sebut game openworld. Selain itu, Ketika kita sedang eksplore hutan akan ada rintangan seperti makhluk aneh yang akan menyerang kita, di game ini kita di siapkan alat senjata yaitu busur dan anak panah untuk menyerang ketika ada monster yang mendatangi kita untuk mencoba menyerang, sehingga kita harus bisa survive Ketika sedang eksplore di hutan. Selain itu juga di game ini kita dapat mengambil dan menyimpan buah-buahan seperti apel di inventory untuk bisa bertahan hidup.
## 1.2 Deskripsi Teknologi Informasi
Tenologi yang di gunakan dalam game ini yaitu :

• Platform yang digunakan dalam game ini yaitu game engine Godot.

• Desain Grafis dan Animasi yang digunakan dalam game ini yaitu menggunakan Assets seperti karakter,monster, latar belakang, animasi,        dan objek lainnya.

• Bahasa pemograman yang digunakan dalam game ini yaitu menggunakanan bahasa Godot itu sendiri yaiut GDscript.
## 1.3 Branding
• Merk : Kibo The Explorer

• Tagline : Survival tetapi menyenangkan

• Campaign : Memperlihatkan game survival atau RPG tetapi dengan tampilan yang tidak menyeramkan tetapi menyenangkan, agar anak-anak bisa mencoba memainkan game bertemakan RPG sekaligus survival.

• Target user :
-	Usia 6+
-	Orang yang senang dengan game survival
-	Penggemar RPG
-	Seorang yang menyukai game survival tetapi takut dengan tampilan game yang menyeramkan
-	Orang yang gemar game petualangan
-	Orang yang gemar dengan tampilan game yang menghibur

• User experience theme :
-   Tampilan yang menghibur
-	Menyenangkan
-	Mudah
-	Warna yang cerah-cerah atau saat siang hari

• Inspirasi Design
![image](https://github.com/Daapputra/ProjekUTS/assets/148644036/81bcabcb-e58d-4d9b-af6a-7e9c49ecd43a)
Ketika user menggerakan karakter akan berpindah map/ latar belakag

![image](https://github.com/Daapputra/ProjekUTS/assets/148644036/9d471e90-a709-43f5-8ee7-83dabfb80360)



## 2.User Story
Sebagai  |   saya ingin bisa      |        Sehinnga			                        |    Prioritas
---|---|---|---
Pemain   |  Menjelajah map yang ada      | Dapat melihat ada apa saja yang ada di dalam game | ⭐⭐⭐⭐⭐
Pemain   |   Membunuh Makhluk aneh yang berkeliaran   |  Dapat merasakan survival di dalam game   |  ⭐⭐⭐⭐⭐
Pemain   |   Mengambil buah buahan      |   Dapat mengambil apel di pohon secara langsung  |    ⭐⭐⭐⭐
Pemain   |  Dapat menggunakan busur  |  Dapat menyerang musuh | ⭐⭐⭐⭐
Pemain | Dapat menyelam ke danau | Dapat bisa mendapatkan sumber makanan dari sungai | ⭐⭐⭐
Pemain | Dapat melemparkan anak panah | musuh dapat di serang dengan anak panah |  ⭐⭐⭐⭐
Pemain | Dapat menyimpan bahan makanan | bahan makanan dapat di kumpulkan di inventory | ⭐⭐⭐⭐
Pemain | Dapat menyimpan anak panah | untuk berjaga-jaga bila anak panah habis terpakai | ⭐⭐⭐
Pemain | Dapat memburu hewan | untuk bahan makanan atau bahan keperluan untuk bertahan hidup | ⭐⭐⭐
Pemain | Dapat membuat tempat tinggal | agar terdapat tempat untuk berlindung | ⭐⭐⭐⭐



## 3.Struktur Data

 ```mermaid
erDiagram
   
    GAME||--o{ KARAKTER : memiliki  
    PEMAIN ||--o{ GAME : bermain
    PEMAIN ||--o{ NYAWA : memiliki
    KARAKTER ||--o{ MAP : menjelajah
    KARAKTER ||--O{ MONSTER : menyerang
```
  
  
## 4.Arsitektur Sistem

 ```mermaid  
   
   %%{init: {"flowchart": {"htmlLabels": false}} }%%
flowchart LR
subgraph " "
  a("FRONTEND
  ") -- "MEMILIKI" --> b{{"GODOT"}}
end
subgraph "****"
  c("BACKEND
  ") -- " MEMILIKI " --> d("GDcript")
end

```


## 5. Teknologi, Library, dan Framework
- Bahasa yg digunakan untuk game ini yaitu GDscript, bahasa di Godot itu sendiri
- Library dan Framework yang digunakan yaitu OpenGL : Godot menggunakan OpenGL untuk rendering grafis.


## 6.Design User Experience dan User Interface

![Screenshot (19)](https://github.com/Daapputra/ProjekUTS/assets/148644036/ea7b3f27-8267-4d16-a9dd-bcb2829bc8ff)

Ketika user menggerakan karakter ke atas, map/latar belakang akan berpindah seperti gambar di bawah ini

![Screenshot (20)](https://github.com/Daapputra/ProjekUTS/assets/148644036/0faa3933-a968-48fa-8b4e-13497e63781d)

Ketika user menggerakan karakter ke bawah, map/latar belakang akan berpindah seperti gambar di bawah ini

![Screenshot (21)](https://github.com/Daapputra/ProjekUTS/assets/148644036/4ca7b200-38b3-4055-9a02-6601cb989f64)




 





