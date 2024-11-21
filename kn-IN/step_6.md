## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

ನಿಮ್ಮ ಟೈಮರ್ ಹೀಗೆ ಮಾಡಬೇಕು:

+ 10 ಸೆಕೆಂಡುಗಳಲ್ಲಿ ಪ್ರಾರಂಭಿಸಬೇಕು
+ ಪ್ರತಿ ಸೆಕೆಂಡಗೆ ಏಣಿಕೆ ಮಾಡಿ

ಟೈಮರ್ 0 ಗೆ ಬಂದಾಗ ಆಟವು ನಿಲ್ಲಬೇಕು.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

ನಿಮ್ಮ ಆಟದ ಕಷ್ಟದ ಮಟ್ಟವನ್ನು ನಿಮಗೆ ಸಂತೋಷವಾಗುವವರೆಗೆ ಕೆಲವು ಬಾರಿ ಬದಲಾಯಿಸಿ ಮತ್ತು ಪರೀಕ್ಷಿಸಿ.

\--- /task \---