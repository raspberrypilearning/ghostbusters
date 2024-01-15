## Анімація привида

--- task ---

Відкрий новий порожній проєкт Скретч.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Додай новий спрайт привида і підходяще тло для Сцени.

![знімок екрану](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Додай код у спрайт привида, щоб він весь час з’являвся і зникав, поки натиснуто зелений прапор.

--- hints ---
--- hint ---

Як тільки `зелений прапор натиснуто`{:class="block3events"}, твій привид повинен `сховатися`{:class="block3looks"} на `одну секунду`{:class="block3control"}, а потім — `показатися`{:class="block3looks"} протягом `однієї секунди`{:class="block3control"}. Він має це робити `завжди`{:class="block3control"}.

--- /hint ---
--- hint ---

Тобі будуть потрібні наступні блоки коду:

![спрайт привида](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint ---
--- hint ---

Ось як має виглядати твій код:

![спрайт привида](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint ---
--- /hints ---

--- /task ---

--- task ---

Протестуй та збережи свій проєкт.

[[[generic-scratch3-saving]]]

--- /task ---