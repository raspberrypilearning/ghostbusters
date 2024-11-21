## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Fe ddylai dy amserydd:

+ Gychwyn ar 10 eiliad
+ Gyfrif i lawr bob eiliad

Fe ddylai’r gêm ddod i ben pan mae’r amserydd yn cyrraedd 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
pan fo'r flag werdd yn cael ei glicio
gosod [amser v] i [10]
ailadrodd hyd at < (amser) = [0] >
 aros (1) eiliad
 newid [amser v] gan (-1)
end
aros [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---