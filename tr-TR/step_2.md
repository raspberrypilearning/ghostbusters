## Bir hayaleti canlandırın

\--- task \---

Yeni bir boş Scratch projesi açın.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Projenize, uygun yeni bir hayalet kuklası ile Sahne arkaplan resmi ekleyin.

![ekran görüntüsü](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Yeşil bayrağa tıklatıldığında, hayaletinizin sonsuza dek görüneceği ve kaybolacağı kodu ekleyin.

\--- hints \--- \--- hint \---

Bir kez `yeşil bayrak tıklandığında`{:class="block3events"}, hayaletiniz `bir saniye`{:class="block3control"} boyunca `gizlenecek`{:class="block3looks"} ve sonrasında `bir saniye`{:class="block3control"} boyunca `gözükecektir`{:class="block3looks"}. Bunu da `sonsuz`{: class = "block3control"} bir döngüde yapması gerekir.

\--- /hint \--- \--- hint \---

İhtiyacınız olan kod blokları:

![hayalet-kuklası](images/ghost-sprite.png)

```blocks3
gizle

göster

sürekli tekrarla
end

(1) saniye bekle

(1) saniye bekle

yeşil bayrak tıklandığında
```

\--- /hint \--- \--- hint \---

Kodunuz şöyle görünmelidir:

![hayalet-kuklası](images/ghost-sprite.png)

```blocks3
yeşil bayrak tıklandığında
sürekli tekrarla 
 gizle
 (1) saniye bekle
 göster
 (1) saniye bekle
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Projenizi test edin ve kayıt edin.

[[[generic-scratch3-saving]]]

\--- /task \---