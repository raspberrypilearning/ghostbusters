## Animando un fantasma

\--- task \---

Abre un nuevo proyecto vacío de Scratch.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Añade una nueva figura de un fantasma y un fondo de escenario adecuado.

![captura de pantalla](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Agrega código a tu fantasma para que siempre aparezca y desaparezca cuando se haga clic en la bandera verde.

\--- hints \--- \--- hint \---

`al hacer clic en la bandera verde`{:class=”blockevents”}, tendrás que hacer `esconder`{:class=”blocklooks”} a tu fantasma, `esperar un segundo`{:class=”blockcontrol”} y después ` mostrar`{:class=”blocklooks”} y `esperar un segundo`{:class=”blockcontrol"}. Tendrá que hacer esto `por siempre`{:class=”blockcontrol"}.

\--- /hint \--- \--- hint \---

Aquí están los bloques de código que necesitas:

![objeto fantasma](images/ghost-sprite.png)

```blocks3
esconder

mostrar

por siempre

esperar (1) segundos

esperar (1) segundos

al hacer clic en la bandera
```

\--- /hint \--- \--- hint \---

Así es como debería verse tu código:

![objeto fantasma](images/ghost-sprite.png)

```blocks3
al hacer clic en la bandera
por siempre
esconder
esperar (1) segundos
mostrar
esperar (1) segundos
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Prueba y guarda tu proyecto.

[[[generic-scratch3-saving]]]

\--- /task \---