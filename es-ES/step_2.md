## Animando un fantasma

--- task ---

Abre un nuevo proyecto vacío de Scratch.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Añade un nuevo objeto fantasma y un fondo de escenario adecuado.

![Captura de pantalla](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Añade código a tu objeto fantasma para que el fantasma aparezca y desaparezca para siempre cuando se haga clic en la bandera verde.

--- hints ---
 --- hint ---

Una vez que `hagas clic en la bandera verde`{:class="block3events"}, tu fantasma debería `esconderse`{:class="block3looks"} durante `un segundo`{:class="block3control"} y después `mostrarse`{:class="block3looks"} durante `un segundo`{:class="block3control"}. Tendrá que hacer esto `por siempre`{:class="block3control"}.
--- /hint ---
 --- hint ---

Aquí están los bloques de código que necesitas: ![objeto fantasma](images/ghost-sprite.png)

```blocks3
esconder

mostrar

por siempre
fin

esperar (1) segundos

esperar (1) segundos

al presionar bandera verde
```

--- /hint --- --- hint --- Así es cómo debería verse tu código: ![objeto fantasma](images/ghost-sprite.png)

```blocks3
al presionar bandera verde
por siempre
esconder
esperar (1) segundos
mostrar
esperar (1) segundos
fin
```

--- /hint ------ /hints ---

--- /task ---

--- task ---

Prueba y guarda tu proyecto.

[[[generic-scratch3-saving]]]

--- /task ---