## Add a score

இப்போது நீங்கள் மதிப்பெண்ணை வைத்து உங்கள் விளையாட்டை மிகவும் சுவாரஸ்யமாக்கப் போகிறீர்கள்!

\--- task \---

`Score`{:class="block3variables"}(மதிப்பெண்) எனப்படும் ஒரு புதிய மாறியை (variable) உருவாக்கவும்.

[[[generic-scratch3-add-variable]]]

\--- /task \---

Keep track of the player's score. Each time a player clicks on a ghost, their score should increase.

![அதிகரிக்கும் மதிப்பெண்](images/ghost-score-test.png)

\--- task \---

Add this code to your ghost sprite:

![பேய்-sprite](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+change [score v] by (1)
```

\--- /task \---

\--- task \---

Test your code. When you click the ghost, it should disappear and the score should change by 1.

\--- /task \---

\--- task \---

Add code to your ghost so that the score resets when a new game starts:

![பேய்-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
+set [score v] to (0)
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

\--- /task \---