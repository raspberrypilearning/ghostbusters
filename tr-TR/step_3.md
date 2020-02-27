## Rastgele hayaletler

Hayaletiniz şu anda kolayca yakalanabilir durumda çünkü hareket etmiyor!

--- task ---

Hayaletinize, aynı konumda kalmak yerine, Sahne Alanı'nda rastgele konumlarda görünecek şekilde kod ekleyebilir misiniz?

--- hints ---

--- hint ---

Hayaletiniz görünmeden önce her seferinde Sahne Alanı'nda rastgele bir konuma `gitmelidir`{:class="block3motion"}.

--- /hint --- --- hint ---

Burada kullanabileceğiniz iki grup kod bloğu vardır. Dilediğiniz kodlama setini seçin.

![hayalet-kuklası](images/ghost-sprite.png)

Ya bu kod bloğunu hayalet kuklanıza ekleyin:

```blocks3
(rastgele konum v) 'e git
```

Ya da kuklanıza bu kodu ekleyin:

```blocks3
x: (14) y: (50) konumuna git

(1) ile (10) arasında rastgele sayı seç

(1) ile (10) arasında rastgele sayı seç
```

--- /hint ---

--- hint ---

Kodunuz şunun gibi görünebilir:

![hayalet-kuklası](images/ghost-sprite.png)

```blocks3
yeşil bayrak tıklandığında
sürekli tekrarla 
 gizle
 (1) saniye bekle
 (rastgele konum v) 'e git
 göster
 (1) saniye bekle
end
```

Veya şöyle görünebilir:

![hayalet-kuklası](images/ghost-sprite.png)

```blocks3
yeşil bayrak tıklandığında
sürekli tekrarla 
 gizle
 (1) saniye bekle
 x: ((-150) ile (150) arasında rastgele sayı seç) y: ((-150) ile (150) arasında rastgele sayı seç) konumuna git
 göster
 (1) saniye bekle
end
```

--- /hint --- --- /hints ---

--- /task ---