## Willekeurige spoken

Je spook is op dit moment heel gemakkelijk te vangen, omdat hij niet beweegt!

\--- task \----

Kun je code aan je spook toevoegen, zodat die op willekeurige posities op het scherm verschijnt, in plaats van steeds op dezelfde plaats?

\--- hints \---

\--- hint \---

Elke keer voordat je spook verschijnt, moet deze `ga naar`{:class="block3motion"} een willekeurige positie in het speelveld.

\--- /hint \--- \--- hint \---

Er zijn twee sets codeblokken die je hier kunt gebruiken. Kies zelf de set die je wilt gebruiken.

![spook-sprite](images/ghost-sprite.png)

Voeg deze set blokken toe aan je Ghost Sprite:

```blocks3
ga naar (willekeurige positie v)
```

Of voeg anders deze toe aan je sprite:

```blocks3
ga naar x: (14) y: (50)

willekeurig getal tussen (1) en (10)

willekeurig getal tussen (1) en (10)
```

\--- /hint \---

\--- hint \---

Je code zou er als volgt uit kunnen zien:

![spook-sprite](images/ghost-sprite.png)

```blocks3
wanneer groene vlag wordt aangeklikt
herhaal
verdwijn
wacht (1) sec.
ga naar (willekeurige positie v)
verschijn
wacht (1) sec.
end
```

Of het zou er als volgt uit kunnen zien:

![spook-sprite](images/ghost-sprite.png)

```blocks3
wanneer groene vlag wordt aangeklikt
herhaal
verdwijn
wacht (1) sec.
ga naar x: (willekeurig getal tussen (-150) en (150)) y: (willekeurig getal tussen (-150) en (150))
verschijn
wacht (1) sec.
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---