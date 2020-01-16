## أضف مؤقت

والان ستقوم باضافة مؤقت بحيث لا يتوفر للاعب سوى 10 ثواني لاصطياد أكبر عدد ممكن من الاشباح.

\--- task \---

أنشئ متغيرًا جديدًا يُسمى 'الوقت'.

\--- /task \---

\--- task \---

هل تستطيع إضافة مؤقت الى المنصة لتمنح اللاعب 10 ثواني لاصطياد الاشباح؟

يجب برمجة الموقِت على النحو التالي:

+ يبدأ العد من 10 ثوان
+ يبدأ في العد التنازلي بمقدار ثانية واحدة

ستنتهي اللعبة عندما يصل الموقِت إلى 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![كائن الشبح](images/ghost-backdrop.png)

```blocks3
أوقف [all]

< [ ] = [ ] >

اجعل [الوقت v] مساوياً [10]

غيّر [الوقت v] بمقدار (-1)

(الوقت)

انتظر (1) ثانية

كرر حتى < >
انتهاء

عند نقر العلم

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

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

\--- /hint \--- \--- /hints \---

\---/task\---

\--- task \---

Ask a friend to test your game. How many points can they score?

\---/task\---

If your game is too easy, you can:

+ منح اللاعب وقتًا أقل
+ اجعل ظهور الأشباح أقل
+ تصغير أحجام الأشباح

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\---/task\---