## Aggiungi un punteggio

Rendiamo il gioco più interessante tenendo il punteggio.

+ Per tenere il punteggio del giocatore, ti serve un posto dove collocarlo. Una __variabile__ è un posto dove conservare i dati che possono cambiare, proprio come un punteggio.

	Per creare una nuova variabile, clicca sulla scheda 'Scripts', seleziona `Variabili e liste` {.blockdata} e poi clicca 'Crea una Variabile'.

	![screenshot](images/ghost-score.png)

	Digita 'punteggio' nel nome della variabile, assicurati che sia disponibile per tutti gli sprite e clicca 'OK' per crearla. Vedrai dunque tanti blocchi di codici che possono esere usati con la tua variabile `punteggio` {.blockdata}.

	![screenshot](images/ghost-variable.png)

	Vedrai il punteggio in alto a sinistra del quadro.

	![screenshot](images/ghost-stage-score.png)

+ Quando si inizia una nuova partita (cliccando la bandiera), dovresti resettare il punteggio del giocatore a 0;

	```blocks
	quando si clicca sulla bandiera verde
	porta [punteggio v] a [0]
	```

+ Ogni volta che si acchiappa una fantasma, devi aggiungere 1 al punteggio del giocatore;

	![screenshot](images/ghost-change-score.png)

+ Esegui di nuovo il programma e acchiappa qualche fantasma. Il tuo punteggio cambia?
