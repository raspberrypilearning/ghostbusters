## ಅಂಕ ಸೇರಿಸಿ

ಈಗ ನೀವು ಅಂಕ ಇಟ್ಟುಕೊಂಡು ನಿಮ್ಮ ಆಟವನ್ನು ಹೆಚ್ಚು ಆಸಕ್ತಿಕರಗೊಳಿಸಲಿದ್ದೀರಿ!

\--- task \---

`score`{:class = "block3variables"} ಎಂಬ ಹೊಸ ವೇರಿಯಬಲ್ ಅನ್ನು ರಚಿಸಿ.

[[[generic-scratch3-add-variable]]]

\--- /task \---

\--- task \---

ಆಟಗಾರನ ಅಂಕವನ್ನು ನೀವು ಗಮನಿಸಬಹುದೇ? ಆಟಗಾರರು ಭೂತಗಳನ್ನು ಹಿಡಿಯಲು ಅವುಗಳ ಮೇಲೆ ಕ್ಲಿಕ್ ಮಾಡಿದಾಗ ಅಂಕಗಳನ್ನು ಗಳಿಸಬೇಕು.

ಪ್ರತಿ ಬಾರಿ ಆಟಗಾರನು ಭೂತದ ಮೇಲೆ ಕ್ಲಿಕ್ ಮಾಡಿದಾಗ, ಅವರ ಅಂಕ ಹೆಚ್ಚಾಗಬೇಕು.

![Increasing score](images/ghost-score-test.png)

\--- hints \--- \--- hint \---

`When the green flag is clicked<code>{:class="block3events"}, ನಿಮ್ಮ <code>score`{:class="block3variables"} ವೇರಿಯೇಬಲ್ ಅನ್ನು <0>set to 0</code>{:class="block3variables"} ಗೆ ಹೊಂದಿಸಬೇಕು. ಕೋಡ್ ಅನ್ನು ಸೇರಿಸಲು ಸ್ಟೇಜ್ ಉತ್ತಮ ಸ್ಥಳ.

`When the ghost sprite is clicked`{:class="block3events"}, `score`{:class="block3variables"} ವೇರಿಯೇಬಲ್ ಅನ್ನು `changed by 1`{:class="block3variables"} ರ ಪಟ್ಟು ಬದಲಾಯಿಸಬೇಕು.

\--- /hint \--- \--- hint \---

ನಿಮಗೆ ಅಗತ್ಯವಿರುವ ಕೋಡ್ ಬ್ಲಾಕ್‌ಗಳು ಇಲ್ಲಿವೆ:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
set [score v] to (0)

when flag clicked
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
change [score v] by (1)
```

\--- /hint \--- \--- hint \---

![backdrop icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [score v] to (0)
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide

+ change [score v] by (1)
```

\--- /hint \--- \--- /hints \---

\--- /task \---