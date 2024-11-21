## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

आपला टाइमर असावा:

+ 10 सेकंदात प्रारंभ करा
+ प्रत्येक सेकंदाला मोजा

जेव्हा टाइमर 0 वर जाईल तेव्हा खेळ थांबला पाहिजे.

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

आपला गेम त्याच्या अडचणीच्या पातळीवर आनंदी होईपर्यंत काही वेळा आपला गेम बदला आणि चाचणी घ्या.

\--- /task \---