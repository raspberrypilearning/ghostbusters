## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

आपकी घड़ी को चाहिए कि:

+ 10 सेकंड से शुरू करें
+ हर सेकंड को गिने

घड़ी के 0 पर पहुंचने पर खेल बंद हो जाना चाहिए।

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![बैकड्रॉप आइकन](images/ghost-backdrop.png)

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

अपने गेम को तब तक बदलें और परखें जब तक कि आप इसके कठिनाई स्तर से खुश न हों।

\--- /task \---