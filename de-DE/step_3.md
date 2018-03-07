## Zufällige Position

Dein Gespenst kann ganz einfach gefangen werden, da es immer an der selben Stelle auftaucht!

+ Damit dass das Gespenst nicht immer an der gleichen Stelle erscheint, kannst Du es bewegen. Hierfür sagst Du Scratch, dass es zufällige Positionen für die Koordinaten x und y vergeben soll. Füge Deinem Code einen `gehe zu` {.blockmotion} Block hinzu, so dass der Code so aussieht:

	```blocks
		Wenn die grüne Flagge angeklickt
		wiederhole fortlaufend
			verstecke dich
			warte (1) Sek.
			gehe zu x:(Zufallszahl von (-150) bis (150)) y:(Zufallszahl von (-150) bis (150))
			zeige dich
			warte (1) Sek.
		Ende
	```

+ Teste Dein Spiel und Du wirst sehen, dass das Gespenst nun jedes Mal an einer anderen Stelle auftaucht.

--- challenge ---
## Herausforderung: Mehr Zufälligkeit
Kannst Du Dein Gespenst eine zufällige Zeit warten lassen, bevor es wieder auftaucht? Versuche es mit dem Befehl `warte` {.blockcontrol} und 'Zufallszahl'. Kannst Du Deinem Gespenst mit `setze Größe` {.blocklooks} jedes Mal eine zufällige Größe geben?
--- /challenge ---
