## Willekeurige spoken

Je spook is op dit moment heel gemakkelijk te vangen, omdat hij niet beweegt!

--- task ---

Kun je code aan je spook toevoegen, zodat die op willekeurige posities op het scherm verschijnt, in plaats van steeds op dezelfde plaats?

--- hints ---


--- hint ---

Elke keer voordat je spook verschijnt, moet deze `ga naar`{:class="block3motion"} een willekeurige positie in het speelveld.

--- /hint --- --- hint ---

Er zijn twee sets codeblokken die je hier kunt gebruiken. Kies zelf de set die je wilt gebruiken.

![spook-sprite](images/ghost-sprite.png)

Voeg deze set blokken toe aan je Ghost Sprite:

```blocks3
go to (willekeurige positie v)
```

Of voeg anders deze toe aan je sprite:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

Je code zou er als volgt uit kunnen zien:

![spook-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

Of het zou er als volgt uit kunnen zien:

![spook-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---