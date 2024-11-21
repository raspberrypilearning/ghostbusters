## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

يجب برمجة الموقِت على النحو التالي:

+ يبدأ العد من 10 ثوان
+ يبدأ في العد التنازلي بمقدار ثانية واحدة

ستنتهي اللعبة عندما يصل الموقِت إلى 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\---/task\---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
عند نقر العلم
اجعل [الوقت v] مساوياً [10]
كرر حتى < (الوقت) = [0] >
انتظر (1) ثانية
غيّر [الوقت v] بمقدار (-1)
انتهاء
أوقف [all]
```

\---/task\---

\--- task \---

Ask a friend to test your game. How many points can they score?

\---/task\---

\--- task \---

غيِّر واختبر لعبتك عدد من المرات حتى تصل إلى مستوى الصعوبة الذي تريده.

\---/task\---