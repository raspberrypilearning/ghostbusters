## ಭೂತವನ್ನು ಅನಿಮೇಟ್ ಮಾಡಿ

\--- task \---

ಹೊಸ ಖಾಲಿ ಸ್ಕ್ರ್ಯಾಚ್ ಯೋಜನೆಯನ್ನು ತೆರೆಯಿರಿ.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Add in a new ghost sprite and a suitable Stage backdrop.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Add code to your ghost sprite so that the ghost appears and disappears forever when the green flag is clicked.

\--- hints \--- \--- hint \---

` ಹಸಿರು ಧ್ವಜವನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿದ ನಂತರ ` {: class = "block3events"}, ನಿಮ್ಮ ಭೂತವನ್ನು, ` ಒಂದು ಸೆಕೆಂಡಿಗೆ class = "block3looks"}` ` ಕಣ್ಮರೆಯಾಗಬೇಕು ` {: class = "block3control"} ತದನಂತರ ` ಒಂದು ಸೆಕೆಂಡಿಗೆ class = "block3looks"}<code>ಗೋಚರಿಬೇಕು` {:class = "block3looks"}. ಇದನ್ನು ಶಾಶ್ವತವಾಗಿ ` ಮಾಡಬೇಕು ` {:class="block3control"}.

\--- /hint \--- \--- hint \---

ನಿಮಗೆ ಅಗತ್ಯವಿರುವ ಕೋಡ್ ಬ್ಲಾಕ್‌ಗಳು ಇಲ್ಲಿವೆ:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

\--- /hint \--- \--- hint \---

ನಿಮ್ಮ ಕೋಡ್ ಹೀಗಿರಬೇಕು:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

ನಿಮ್ಮ ಯೋಜನೆಯನ್ನು ಪರೀಕ್ಷಿಸಿ ಮತ್ತು ಉಳಿಸಿ.

[[[generic-scratch3-saving]]]

\--- /task \---