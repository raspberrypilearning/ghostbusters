## Animando um fantasma

\--- task \---

Abra um novo projeto no Scratch.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Adicione um novo fantasma e um pano de fundo adequado.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Adicione código no seu fantasma para que o fantasma apareça e desapareça sempre quando a bandeira verde for clicada.

\--- hints \--- \--- hint \---

Once the `green flag is clicked`{:class="block3events"}, your ghost should `hide`{:class="block3looks"} for `one second`{:class="block3control"} and then `show`{:class="block3looks"} for `one second`{:class="block3control"}. It needs to do this `forever`{:class="block3control"}. \--- /hint \--- \--- hint \---

Here are the code blocks you need: ![ator do fantasma](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

\--- /hint \--- \--- hint \--- This is what your code should look like: ![ator do fantasma](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Teste e salve seu projeto.

[[[generic-scratch3-saving]]]

\--- /task \---