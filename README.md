### Demo
#### https://mjniuz.github.io/typer

Typer Problem
    
Kita mencari developer yang mandiri, ketika ada masalah, aktif mencari solusi dengan sendirinya dan mudah mengerti instruksi tanpa terlalu banyak menanyakan untuk memahami instruksi.     
Berikut adalah aplikasi Javascript yang simple.    
Kami tidak akan menjelaskan bagaimana cara kerjanya atau library apa yang dipakai.   
    
Pertanyaan:   
1. Sebutkan library apa saja yang dipakai, website library itu dimana, dan dokumentasi library itu ada dimana.
    a. Bootstrap
        Source  : getbootstrap.com
        Docs    : http://getbootstrap.com/css/

    b. JQuery 1.11.1
        Source  : https://blog.jquery.com/2014/05/01/jquery-1-11-1-and-2-1-1-released/
        Docs    : http://api.jquery.com/

    c. JQuery UI 1.10.4
        Source  : http://jqueryui.com
        Docs    : http://api.jqueryui.com/

    d. Backbone.js 1.1.2
        Source  : http://backbonejs.org
        Docs    : http://backbonejs.org/#API-integration

    e. Underscore.js 1.6.0
        Source  : http://underscorejs.org
        Docs    : http://underscorejs.org/#collections

    f. Glyphicon
        Source  : http://glyphicons.com/
        Docs    : http://glyphicons.com/examples-of-use/

2. Aplikasi itu 'laggy'. Kenapa? Bagaimana cara membuat animasi lebih 'smooth'?

    - Kalau "laggy" yang dimaksud adalah lambat karena "waktu" bisa dirubah saja `animation_delay` ke lebih kecil yaitu `0` atau `10`,
    Dikarenakan value setInterval yang tinggi dapat menyebabkan performa gerakan menjadi lebih lamban

3. Aplikasi itu tidak akan jalan di salah satu 3 browser populer (Chrome, Firefox, Internet Explorer)? Kenapa? Solusinya hanya menghapus satu character di code, character yang mana?    

    - Saya coba di Mozilla, Chrome, IE dan Microsoft Edge tidak ada masalah untuk memainkan game nya.
    Namun kemungkinan (highlight notif pada IDE PHPStorm) berasal dari koma pada Typer default,

4. Implementasikan tombol Start, Stop, Pause, dan Resume.

    - Done, Anda bisa testing secara langsung pada demo

5. Ketika ukuran window dirubah, susunan huruf yang 'terbentur' batas window menjadi tidak 1 baris. Benarkan.

    - Done, permasalahan pada css

6. Implementasikan sistem score.

    - Done.

7. Implementasikan hukuman berupa pengurangan nilai bila salah ketik.

    - Done