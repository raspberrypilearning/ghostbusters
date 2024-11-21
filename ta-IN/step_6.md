## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

உங்கள் நேரங்காட்டி பின்வருமாறு:

+ 10 வினாடிகளில் தொடங்க வேண்டும்
+ ஒவ்வொரு நொடியும் பின்னோக்கி எண்ண வேண்டும்(count down)

நேரங்காட்டி 0-க்கு வரும்போது விளையாட்டு நிறுத்தப்பட வேண்டும்.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![பின்னணி icon](images/ghost-backdrop.png)

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

உங்கள் விளையாட்டின் கடின அளவில்(difficulty level) நீங்கள் திருப்தி அடையும்வரை, உங்கள் விளையாட்டை சில முறை மாற்றி மாற்றி, சோதித்துப் பாருங்கள்.

\--- /task \---