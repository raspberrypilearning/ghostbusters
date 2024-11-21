## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Pengatur waktu kamu harus:

+ Mulai dari 10 detik
+ Menghitung mundur setiap detik

Game harus berhenti saat pengatur waktu menjadi 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /tugas \---

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

\--- /tugas \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /tugas \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /tugas \---