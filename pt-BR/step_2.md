## Animando um fantasma

--- task ---

Abra um novo projeto no Scratch.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Adicione um novo fantasma e um pano de fundo adequado.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Adicione código no seu fantasma para que o fantasma apareça e desapareça sempre quando a bandeira verde for clicada.

--- hints ---
 --- hint ---

Uma vez que a `bandeira verde é clicada`{:class="block3events"}, seu fantasma deve se `esconder`{:class="block3looks"} por `um segundo`{:class="block3control"} e então `mostrar`{:class="block3looks"} por `um segundo`{:class="block3control"}. Ele precisa fazer isso para `sempre`{:class="block3control"}.
--- /hint ---
 --- hint ---

Aqui estão os blocos de código que você precisa:![ator do fantasma](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint --- --- hint --- Seu código deve ficar assim: ![ator do fantasma](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint ------ /hints ---

--- /task ---

--- task ---

Teste e salve seu projeto.

[[[generic-scratch3-saving]]]

--- /task ---