## சீரற்ற பேய்கள்

இப்போது உங்கள் பேயை நீங்கள் எளிதில் பிடிக்கலாம், ஏனென்றால் அது நகரவில்லை!

\--- task \---

உங்கள் பேய் ஒரே நிலையில் இருக்காமல், மேடையில் வேறு வேறு இடங்களில், சீரற்ற நிலைகளில்(random positions) தோன்ற வேண்டும். இதற்கான குறியீட்டை உங்கள் பேய் sprite - இல் சேர்க்க முடியுமா?

\--- hints \---

\--- hint \---

உங்கள் பேய் தோன்றுவதற்கு முன்பு ஒவ்வொரு முறையும், மேடையில் ஒரு சீரற்ற நிலைக்கு செல்ல வேண்டும்(`go to`{:class="block3motion"}).

\--- /hint \--- \--- hint \---

நீங்கள் இங்கே பயன்படுத்தக்கூடிய இரண்டு குறியீடு தொகுதிகள் உள்ளன. நீங்கள் விரும்பும் தொகுப்பைத் தேர்வுசெய்க.

![பேய்-sprite](images/ghost-sprite.png)

ஒன்று, உங்கள் பேய் sprite-இல் இந்த தொகுதிகளை சேர்க்கவும்:

```blocks3
go to (random position v)
```

அல்லது இதை உங்கள் sprite-க்கு சேர்க்கவும்:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

\--- /hint \---

\--- hint \---

உங்கள் குறியீடு இதுபோன்றதாக இருக்கலாம்:

![பேய்-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

அல்லது இவ்வாறு இருக்கலாம்:

![பேய்-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---