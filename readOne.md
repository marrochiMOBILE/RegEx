# Mengenal Regular Expressions
Regular expressions adalah template untuk data berdasarkan pola tertentu. Tutorial ini akan mendemonstrasikan kemampuan regular expression tanpa bergantung pada bahasa pemrograman tertentu

## link buat belajar nyoba regex
#### ``` https://regexr.com/ ```

## link buat keterangan regex
#### ``` https://www.zytrax.com/tech/web/regex.htm ```

## regex diawali dengan / dan ditutup dengan /

#### contoh 1
``` /sion/g ``` artinya cari dari satu baris yang ada kata sion

##### ``` /g ``` disini membaca semua menjadi satu baris

#### contoh 2
``` /[res]/g ``` artinya dia akan membaca dengan beberapa option. intinya dia angka membaca per character yg ada didalam option

#### contoh 3
``` /[a-z]/g ``` artinya dia akan membaca perkarakter dari hurf kecil a sama z

#### contoh 4
``` /[a-z0-9]/g ``` artinya dia akan membaca perkarakter dari hurf kecil a sampai z dan 0 sampai 9

#### contoh 5
``` /[^a-z0-9A-~]/g ``` maksud dari  ```^``` itu artinya kecuali selain opsi didalam

#### contoh 6
``` /cea?/g ``` tanda ```?``` ini dia akan mencari kata yg dimulai dari c ke e dan ke a

#### contoh 7
``` /(mie)?a/g ``` maksudnya itu per group ->  ```(mie)``` jika tidak ada mie maka dimulai membaca a 

#### contoh 8 
``` /koding+/gm ``` maksudnya dari ```+``` cari koding setlah g terkahir dan g seterusnya itu termasuk

#### contoh 9
``` /koding*/gm ``` maksudnya dari ```*``` cari koding walaupun ```g``` nya gada dan setealah ```g``` itu dianggap

#### contoh 10
```/kodingg{2}/hm ``` cari setelah kodin yang huruf ```g``` nya ada 2 . atau bisa ```{2,5}``` artinya minimal dan maksimal. atau bisa {2,} minimal dan tak terhingga

#### contoh 11
``` /^kod/ ``` beda lagi funsi ini ``` ^ ``` untuk mencari awalan kata kod

#### cotoh 12
``` /kod$/ ``` beda lagi funsi ini ``` $ ``` untuk mencari akhiran kata kod

## regex email
#### ``` [a-zA-z_0-9]+@[a-z]+\.(com|org|id)$ ``` 
