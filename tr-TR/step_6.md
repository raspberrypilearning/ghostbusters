## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Zamanlayıcınız şunları yapmalı:

+ 10 saniyede başlamalı
+ Her saniyede 1 azalmalı

Zamanlayıcı 0 olduğunda oyun durmalı.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

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

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Zorluk seviyesinden memnun kalana kadar oyununu birkaç kez değiştir ve test et.

\--- /task \---