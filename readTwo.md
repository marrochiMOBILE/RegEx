# readTwo.md

dibawah ini artinya carikan kata Reg 
```regex
/Reg/g
```
> `Reg`Exr was created by `RegReg` and is proudly hosted by Media Temple.

artinya carikan saya kata Reg yang setekah kata Re dialnjutkan dengan g'nya 2x 
```regex
/Reg{2}/g
```
> RegExr was created by `Regg`g and is proudly hosted by Media Temple.

artinya carikan saya kata reg jika tidak ada reg re pun boleh
```regex
/reg?/g
```
> RegExr was c`re`ated by Reggg and is proudly hosted by Media Temple.`reg`gg rEdit the Exp`re`ssion

artinya carikan saya kata regs jika tidak ada res pun boleh
```regex
/reg?s/g
```
> RegExr `regs`  reg was  `res` re created by Reggg and is proudly hosted by Media Temple.

artinya carikan kata re atau setelah kata r e'nya tidak terhingga
```regex
/re+/g
```
> `reee` `re`gs  `re`g was  `re`s `re` c`re`ated by Reggg and is proudly hosted by Media Temple.

artinya carikan kata rey atau setelah r e'nya tidak terbatas diakhir katanya y
```regex
/re+y/g
```
> `reeey` regs  reg `rey` was  res re created by raya Rrayeggg and is proudly hosted by Media 

artinya carikan saya kata re yg seteleah r nya e'nya tidak terbatas jika tidak ada r pun jadi
```regex
/re*/g
```
> `reee`y `re`gs  `re`g `re`y was  `re`s `re` c`re`ated by `r`aya R`r`ayeggg and is p`r`oudly hosted by Media

artinya carikan saya kata res yang setelah r e'nya tidak terbatas kemudian dilajutkan s atau rs pun jadi
```regex
/re*s/g
```
> `rs` `reees` reg rey was  `res` re created by raya Rrayeggg and is proudly hosted by Media Temple.

artinya semua kata baik space itu dianggap kecualin enter atau (dot).
Ini cocok dengan karakter apa pun, selain baris baru.
```regex
/./g
```
```regex
/gr.y/g
```
> `gray` `grey` `groy` `grby`

artinya cari yg ada titiknya aja
```regex
/\./g
```
> ochi`.` `.` `.` `.`Temple`.`reggg rEdit the Expression & Text to see  matches`.`

artinya carikan saya kata dari group  satu (rs) dan dua (s atau g)
```regex
/(re)(s|g)/g
```
> re Temple.`reg`gg rEdit the Exp`res`sion & Text to see matches.

```regex
/egg(spam)*/g
```
> `egg` `eggspam`

```regex
/ice(-)?cream/g
```

> `ice-cream` `icecream`

dicari dari clas perkata
```regex
/[aiueo]/g
```
> `a` `i` `u` `e` `o` 

```regex
 [aiueo]{2, 3}
```

> `ai` `oo` `ueo`

```regex
 [aiueo]{2, }
```

> `ai` `oo` `ueo` `uuuuuuuuueoeeieoeueei`

```regex
/[A-Z][a-z][0-9]/g
```

> `Jk0` JJ8  `Kl7`

artinya `^` didalam class itu artinya yang bukan
```regex
/[^a-z ]/g.md
```

artinya `^` diluar yaitu yg harus diawali
```regex
/^[a-z ]/g
```
