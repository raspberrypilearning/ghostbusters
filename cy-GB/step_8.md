## Ychwanegu Amserydd

Rwyt ti nawr am ychwanegu amserydd fel mai dim ond deg eiliad sydd gan y chwareuwr i ddal cymaint o ysbrydion ag sy'n bosib.

\--- task \---

Creu newidyn newydd o'r enw 'amser'.

\--- /task \---

\--- task \---

Alli di ychwanegu amserydd i'r Llwyfan sydd dim ond yn rhoi 10 eiliad i'r chwareuwr ddal ysbrydion?

Fe ddylai dy amserydd:

+ Gychwyn ar 10 eiliad
+ Gyfrif i lawr bob eiliad

Fe ddylai’r gêm ddod i ben pan mae’r amserydd yn cyrraedd 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![corlun-ysbryd](images/ghost-backdrop.png)

```blocks3
aros [all]

< [ ] = [ ] >

gosod [amser v] i [10]

newid [amser v] gan (-1)

(amser)

aros (1) eiliad

ailadrodd hyd at < >
end

pan fo'r flag werdd yn cael ei glicio

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![eicon cefnlen](images/ghost-backdrop.png)

```blocks3
pan fo'r flag werdd yn cael ei glicio
gosod [amser v] i [10]
ailadrodd hyd at < (amser) = [0] >
 aros (1) eiliad
 newid [amser v] gan (-1)
end
aros [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Rhoi llai o amser i’r chwareuwr
+ Gwneud i’r ysbrydion ymddangos yn llai aml
+ Gwneud yr ysbrydion yn llai

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---