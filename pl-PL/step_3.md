## Losowe duchy

Twój duch jest naprawdę łatwy do złapania, ponieważ się nie porusza!

--- task ---

Czy możesz dodać kod do swojego ducha, aby zamiast pozostawać w tej samej pozycji, duch pojawiał się w losowych miejscach na scenie?

--- hints ---


--- hint ---

Za każdym razem, zanim pojawi się twój duch, powinien `przejść`{:class="block3motion"} do losowej pozycji na scenie.

--- /hint --- --- hint ---

Istnieją dwa zestawy bloków kodu, których możesz użyć tutaj. Wybierz zestaw, który preferujesz.

![duszek ducha](images/ghost-sprite.png)

Dodaj ten zestaw bloków do twojego duszka:

```blocks3
go to (losowa pozycja v)
```

Lub dodaj ten do swojego duszka:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

Twój kod może wyglądać tak:

![duszek ducha](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (losowa pozycja v)
show
wait (1) seconds
end
```

Lub może wyglądać tak:

![duszek ducha](images/ghost-sprite.png)

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