## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

আপনার টাইমার করা উচিত:

+ 10 সেকেন্ডে শুরু করুন
+ প্রতি সেকেন্ডে গণনা করুন

টাইমার 0 এ গেলে খেলা থামানো উচিত।

\--- /task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- /task \---

Add this code to your **Stage**:

![ব্যাকড্রপ আইকন](images/ghost-backdrop.png)

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

\--- /task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- /task \---

আপনার গেমটির অসুবিধার মাত্রা নিয়ে আপনি খুশি না হওয়া পর্যন্ত কয়েকবার আপনার গেমটি পরিবর্তন করুন এবং পরীক্ষা করুন।

\--- /task \---