## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

타이머는 이렇게 동작해야 해요.

+ 10초부터 시작합니다.
+ 매 초 숫자가 줄어듭니다.

타이머가 0이 되면 게임이 끝나야 합니다.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
flag 클릭했을 때
[time v] 를 [10] 로 정하기
< (time) = [0] > 까지 반복하기
(1) 초 기다리기
[time v] 를 (-1) 만큼 바꾸기
끝
정지 [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---