## Animare un fantasma

--- task ---

Avvia un nuovo progetto Scratch.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Aggiungi un nuovo sprite di un fantasma e uno scenario adatto a questo personaggio.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Aggiungi codice al tuo fantasma in modo che appaia e scompaia per sempre quando viene cliccata la bandiera verde.

--- hints ---
 --- hint ---

`quando si clicca sulla bandiera verde`{:class="block3events"}, il tuo fantasma dovrebbe `nascondi`{:class="block3looks"} per `attendi (1) secondi`{:class="block3control"} e poi `mostra`{:class="block3looks"} per `attendi (1) secondi`{:class="block3control"}. Questo lo deve fare `per sempre`{:class="block3control"}.
--- /hint ---
 --- hint ---

Ecco i blocchi di codice che ti serviranno: ![sprite del fantasma](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint --- --- hint --- Ecco come dovrebbe apparire il tuo codice: ![sprite del fantasma](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Prova il tuo progetto e salvalo.

[[[generic-scratch3-saving]]]

--- /task ---
