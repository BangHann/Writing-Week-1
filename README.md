CLI (Command Line Interface)
-
- ### CLI

    Hanya ada teks, tidak ada tampilannya.  || Perbedaan GUI (Graphic User Interface) dengan CLI yaitu GUI berupa tampilan, CLI hanya teks.

    Contoh cli : cmd, bash

- ### SHELL 

    perintah2 yg digunakan untuk menginstruksikan system operasi

- ### Perintah-perintah yang ada di CLI :
    - Pwd : untuk melihat dimana posisi kita berada
    - Ls : untuk melihat isi file apa saja yang ada didalamnya
    - Cd : untuk berpindah direktori/folder. Untuk keluar dari folder : (nama folder) cd..
    - Mkdir : untuk membuat folder baru
    - Head : menampilkan beberapa isi dari baris atas
    - Tail : menampilkan beberapa isi dari baris bawah
    - Cp : untuk mencopy/menyalin file
    - Rm : untuk menghapus file

- ### Git dan Github

    - Git adalah tools untuk programmer berfungsi sebagai control system untuk menjalankan proyek pengembangan software.
    - Github : Github adalah situs web juga sebuah layanan cloud yang bisa membantu para pengguna untuk menyimpan,mengelola dan mengembangkan
    
- ### Command Git:
    - git init : untuk membuat file di repository lokal
    - git status : untuk memgetahui status dari sebuah repository
    - git add : untuk menambahkan file baru di repository
    - git commit : untuk menyimpan perubahan yang sudah dilakukan, tetapi tidak pada remote repository
    - git log : untuk melihat catatan-catatan revisi yang sudah dilakukan
    - git push : untuk mengirimkan perubahan file setelah di commit ke remote repository
    - git branch : untuk melihat semua cabang di repository
    - git checkout: sebuah perintah yang digunakan untuk menukar branch yang aktif dengan branch yang sudah dipilih.
    - git merge: perintah yang digunakan untuk menggabungkan cabang aktif serta cabang yang dipilih
    - git clone: adalah perintah yang digunakan untuk mengkloning repository lokal


- ### HTML (Hypertext Markup Language)

    - Html digunakan untuk menampilkan konten pada web browser
    - Tools yang digunakan untuk html : browser dan visual studio code
    - Html element terdiri dari opening tag, content, closing tag
```html
<p>Hello World</p>
```
- Kerangka Dasar Sebuah Web
```html
  <html>
  <head>
  <title>
      nama website
    </title>
  <body>
      bebas isinya konten website.
    </body>
  </html>
  ```

- Attribute : sebuah properti dari html element
```html
    <h1 id="header"></h1>
    <img src="image.png">
```

- image
```html
<img src="buya.jpeg">
```

- Bold/Miring
```html
<b>Bold</b> <i>Miring</i>
```

- Tulisan Berbentuk Link
```html
<a href="">Tulisan tapi link</a>
```

Output

![Cuplikan layar 2022-09-26 165007](https://user-images.githubusercontent.com/114202925/192453602-73d594ff-100f-4a94-8307-2bd0b2482dc0.png)

- Ordered List
```html
<ol type="a">
        <li>Manusia</li>
        <li>Animers</li>
        <li>WIBU</li>
</ol>
```

output

![image](https://user-images.githubusercontent.com/114202925/192457659-f9fbbd4b-8f83-4a4f-8cb9-d9cb93dc0f0d.png)

- section
```html
<section>
            <h2>Contact me</h2>
            <form action="">
                <label for="">name</label>
                <input type="text" name="" id=""/>
                <label for="">email</label>
                <input type="email" name="" id=""/>
                <button>send</button>
            </form>
</section>
```

output

![image](https://user-images.githubusercontent.com/114202925/192457617-66f15516-63e0-457b-834e-345ea996b315.png)

CSS (Cascading Style Sheet)
-
- CSS untuk memperindah tampilan html
- Cara menggunakan CSS ada 3, yaitu :

    1. Inline CSS
    
    ```html
    <!-- pada html -->
    <h1 style="background-color: yellowgreen">Halo Aku <span>Paran</span></h1>
    ```
    Output
   
   ![image](https://user-images.githubusercontent.com/114202925/192461694-8dce0ce0-284d-4ee5-9cd1-a594725be8a7.png)

    2. Internal CSS
    
    ```html
   !DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <style>
            h1 {
                border: black 1px solid;
            }
        </style>

        <h1>Halo Saya Siapa ya</h1>
    </body>
    </html>
    ```
    Output
    
    ![image](https://user-images.githubusercontent.com/114202925/192462233-970b1a01-3570-44ba-9f84-f6ba969f2fde.png)

    3. Eksternal CSS
    
    - Menggunakan dua file secara terpisah, yaitu file index.hyml dan file style.css
    
    ```html
    <!-- Menyisipkan code berikut pada file html -->
    <link rel="stylesheet" href="iseng.css" />
    <h1 style="background-color: yellowgreen">Halo Aku <span>Paran</span></h1>
    ```
   
    ```css
    /*style.css*/
    h1 {
    padding: 10px 20px 30px;
    /* margin: 0 100px; */
    display: inline-block;
    /* visibility: hidden; */
    width: 50% ;
    border: black solid 5px;
    }
    ```

- Display
    1. Display inline : kotak hanya sebesar konten aja
    2. Display inline-block : mengatur lebar dan tingginya
    3. Display flex : untuk membuat gambar menghilang

- Position
    1. Position static : pada tempatnya
    2. Position relative : bisa diubah2 tempatnya
    3. Position absolute  : bisa  berpindah mengikuti posisi induknya yang relative
   
- Visibility
    1. Visibility none : element menghilang
    2. Visibility hidden : konten masih ada, tetapi tidak terlihat

Algoritma
-
- algoritma : langkah2 yg dibutuhkan untuk menyelesaikan suatu masalah
- setiap orang punya algoritma nya masing2
- jenis2 algoritma : deskriptif, pseudocode, flowchart

Pseudocode
-
- pseudocode : menuliskan algoritma dengan umumnya bahasa inggris sebelum kita implementasikan ke bahasa pemograman tertentu.
- contoh pseudocode menentukan bilangan ganjil dan genap :
   ```
   Deklarasi :
        var bil.integer;
    Deskripsi :
        bil <- 10;
        Read (bil)
        if (bil%2==0) then
            print"Bilangan Genap";
            Else
            print"Bilangan Ganjil";
        End if
    ```
 
Java Script
-
- tipe data : string, number, array, Boolean, null, undefined
```js
let myName = "Paran"
myName = 'Gantenk'
console.log(myName) //output = Gantenk
```
```js
let age = 17 //output = 17
```

- variable : tempat menampung sebuah data
    1. let
    2. const
    3. var

Loop (Perulangan)
-
- For

    ```js
    //for(start; stop; step;)
    for (let i=1; i<= 10; i++){
    console.log(i)
    } //output : 12345678910
    ```
- If Condition

    ```js
    if(i==6){
        console.log (i "yes ketemu")
    } else{
    console.log(i)
    } //output : 6 'yes ketemu'
    ```
- While
 
    ```js
    //cari angka yang dapat dibagi dengan angka 2,3,4,5,6
    i=1
    let isKetemu = false
    while(!isKetemu) {
    if (i%2 == 0 && i%3==0 && i%4 == 0 && i%5 == 0 && i%6 == 0 ){
    Console.log(i);
    isKetemu=true
    } i++
    } //output : 60
    ```
- Do while
   
    ```js
    //cari angka yang dapat dibagi dengan angka 2,3,4,5,6
    do {
        if (
            i % 2 == 0 &&
            i % 3 == 0 &&
            i % 4 == 0 &&
            i % 5 == 0 &&
            i % 6 == 0
        ) {
            console.log(i);
            isKetemu = true
        }
        i++
    } while (!isKetemu) //output : 60
    ```
Function
-
- Cara membuat function ada 3, yaitu :
1. function clasic
  function myfunction(kondisi){ }
  ```js
  function greeting(name = "Paran") {
    console.log(`hallo, apa kabar ${name}?`)
    }
 
    greeting("Kilua") //output : hallo, apa kabar Kilua?
    greeting("Aulia") //output : hallo, apa kabar Aulia?
    greeting("Farhan") //output : hallo, apa kabar Farhan?
    greeting() //output : hallo, apa kabar Paran?
  ```
2. function variable -> let myFunction=function(){ }
3. arrow function -> let myFunction=function(){ }
