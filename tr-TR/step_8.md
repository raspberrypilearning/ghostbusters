## Bir zamanlayıcı ekle

Şimdi bir zamanlayıcı ekleyeceksiniz, böylece oyuncu mümkün olduğu kadar çok hayalet yakalamak için sadece 10 saniyeye sahip olacak.

\--- task \---

'Süre' adlı bir değişken oluşturun.

\--- /task \---

\--- task \---

Sahne Alanı'nıza, oyuncunun hayaletleri yakalayabilmesi için sadece 10 saniye süre tanındığı bir zamanlayıcı ekleyebilir misiniz?

Zamanlayıcınız şunları yapmalı:

+ 10 saniyede başlamalı
+ Her saniyede 1 azalmalı

Zamanlayıcı 0 olduğunda oyun durmalı.

\--- hints \--- \--- hint \---

`Yeşil bayrak tıklandığında`{:class="block3events"}, `puan`{:class="block3variables"} değişkeninizin `10 'a ayarlanması`{:class="block3variables"} gerekir. Daha sonra bu değişken `0'a ulaşıncaya dek`{:class="block3control"} `-1 azalmalıdır`{:class="block3variables"}.

\--- /hint \--- \--- hint \---

İhtiyacınız olan kod blokları:

![hayalet-kuklası](images/ghost-backdrop.png)

```blocks3
durdur [all]

<[ ] = [ ]>

[süre] i [10] yap

[süre] i (-1) kadar değiştir

(süre)

(1) saniye bekle

<> olana kadar tekrarla
end

yeşil bayrak tıklandığında

```

\--- /hint \--- \--- hint \---

Zamanlayıcı oluşturmak için eklemeniz gereken kod:

![zemin simgesi](images/ghost-backdrop.png)

```blocks3
yeşil bayrak tıklandığında
[süre] i [10] yap
<(süre) = [0]> olana kadar tekrarla 
 (1) saniye bekle
 [süre] i (-1) kadar değiştir
end
durdur [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Bir arkadaşınızdan oyununuzu denemesini rica edin. Kaç puan alabilirler?

\--- /task \---

Eğer oyunun çok kolaysa, bunları yapabilirsin:

+ Oyuncuya daha az zaman ver
+ Hayaletleri daha seyrek görünür yap
+ Hayaletleri daha küçük yap

\--- task \---

Zorluk seviyesinden memnun kalana kadar oyununu birkaç kez değiştir ve test et.

\--- /task \---