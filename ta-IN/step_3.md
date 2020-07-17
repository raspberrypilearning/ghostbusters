## சீரற்ற பேய்கள்

உங்கள் பேய் இந்த நேரத்தில் பிடிக்க மிகவும் எளிதானது, ஏனென்றால் அது நகரவில்லை!

\--- task \---

உங்கள் பேயுடன் குறியீட்டைச் சேர்க்க முடியுமா, அதனால் ஒரே நிலையில் இருப்பதற்குப் பதிலாக, பேய் மேடையில் சீரற்ற நிலைகளில் தோன்றும்?

\--- hints \---

\--- hint \---

உங்கள் பேய் தோன்றுவதற்கு ஒவ்வொரு முறையும், அது ` க்கு செல்ல வேண்டும் ` {: class = "block3motion" the மேடையில் ஒரு சீரற்ற நிலை.

\--- /hint \--- \--- hint \---

நீங்கள் இங்கே பயன்படுத்தக்கூடிய இரண்டு குறியீடு தொகுதிகள் உள்ளன. நீங்கள் விரும்பும் தொகுப்பைத் தேர்வுசெய்க.

![பேய்-sprite](images/ghost-sprite.png)

உங்கள் பேய் sprite-இல் இந்த தொகுதிகள் சேர்க்கவும்:

```blocks3
(சீரற்ற நிலை v) க்குச் செல்லவும்
```

அல்லது இதை உங்கள் sprite-இக்கு சேர்க்கவும்:

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

அல்லது இது இப்படி இருக்கக்கூடும்:

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