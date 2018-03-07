## Fantasmas aleatorios

¡Tu fantasma es muy fácil de atrapar, porque no se mueve!

+ En lugar de quedarse en la misma posición, puedes hacer que Scratch elija coordinadas x e y al azar. Añade un bloque `ir a`{:class="blockmotion"} al código de tu fantasma, para que sea como éste:

	```blocks
		al presionar bandera verde
		por siempre
			esconder
			esperar (1) segundos
			ir a x:(número al azar entre (-150) y (150)) y:(número al azar entre (-150) y (150))
			mostrar
			esperar (1) segundos
		fin
	```

+ Vuelve a probar tu fantasma, y deberías de ver cómo aparece cada vez en una posición diferente.

--- challenge ---
## Desafío: Más aleatoriedad
¿Puedes hacer que tu fantasma `espere`{:class="blockcontrol"} un intervalo de tiempo al azar antes de aparecer? ¿Puedes usar el bloque `fijar tamaño`{:class="blocklooks"} para hacer que el tamaño de tu fantasma cambie al azar cada vez que aparezca?
--- /challenge ---
