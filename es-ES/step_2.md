## Animando un fantasma

\--- task \---

Abre un nuevo proyecto vacío de Scratch.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Añade un nuevo objeto fantasma y un fondo de escenario adecuado.

![Captura de pantalla](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Añade código a tu objeto fantasma para que el fantasma aparezca y desaparezca para siempre cuando se haga clic en la bandera verde.

\--- hints \--- \--- hint \---

Once the `green flag is clicked`{:class="block3events"}, your ghost should `hide`{:class="block3looks"} for `one second`{:class="block3control"} and then `show`{:class="block3looks"} for `one second`{:class="block3control"}. It needs to do this `forever`{:class="block3control"}. \--- /hint \--- \--- hint \---

Here are the code blocks you need: ![ghost-sprite](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

\--- /hint \--- \--- hint \--- This is what your code should look like: ![ghost-sprite](images/ghost-sprite.png)

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

Prueba y guarda tu proyecto.

[[[generic-scratch3-saving]]]

\--- /task \---