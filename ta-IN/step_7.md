## மதிப்பெண் சேர்க்கவும்

இப்போது நீங்கள் மதிப்பெண்ணை வைத்து உங்கள் விளையாட்டை மிகவும் சுவாரஸ்யமாக்கப் போகிறீர்கள்!

\--- task \---

` மதிப்பெண் எனப்படும் புதிய variable உருவாக்கவும் ` {: class = "block3variables"}.

[[[generic-scratch3-add-variable]]]

\--- /task \---

\--- task \---

வீரரின் மதிப்பெண்ணைக் கண்காணிக்க முடியுமா? வீரர்கள் பேய்களைப் பிடிக்க அவர்கள் புள்ளிகளைப் பிடிக்க வேண்டும்.

ஒவ்வொரு முறையும் ஒரு வீரர் ஒரு பேயைக் கிளிக் செய்யும்போது, அவர்களின் மதிப்பெண் அதிகரிக்க வேண்டும்.

![மதிப்பெண் அதிகரிக்கும்](images/ghost-score-test.png)

\--- hints \--- \--- hint \---

` பச்சைக் கொடி சொடுக்கும் போது ` {: class = "block3events"}, உங்கள் ` மதிப்பெண் ` {: class = "block3variables"} மாறி ` 0 ஆக அமைக்கப்பட வேண்டும் ` {: class = "block3variables"}. இந்த குறியீட்டைச் சேர்க்க மேடை சிறந்த இடம்.

` பச்சைக் கொடி சொடுக்கும் போது ` {: class = "block3events"}, உங்கள் ` மதிப்பெண் ` {: class = "block3variables"} மாறி ` 1 ஆக அமைக்கப்பட வேண்டும் ` {: class = "block3variables"}.

\--- /hint \--- \--- hint \---

உங்களுக்கு தேவையான குறியீடு தொகுதிகள் இங்கே:

![பின்னணி icon](images/ghost-backdrop.png)

```blocks3
set [score v] to (0)

when flag clicked
```

![பேய்-sprite](images/ghost-sprite.png)

```blocks3
change [score v] by (1)
```

\--- /hint \--- \--- hint \---

![பின்னணி icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [score v] to (0)
```

![பேய்-sprite](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide

+ change [score v] by (1)
```

\--- /hint \--- \--- /hints \---

\--- /task \---