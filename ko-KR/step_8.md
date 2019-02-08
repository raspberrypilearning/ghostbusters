## Add a timer

Now you're going to add a timer so that the player only has ten seconds to catch as many ghosts as possible.

\--- task \---

'시간'이라는 새 변수를 추가합니다.

\--- /task \---

\--- task \---

Can you add a timer to your Stage to give your player only 10 seconds to catch ghosts?

타이머는 이렇게 동작해야 해요.

+ 10초부터 시작합니다.
+ 매 초 숫자가 줄어듭니다.

타이머가 0이 되면 게임이 끝나야 합니다.

\--- hints \--- \--- hint \--- `When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}. \--- /hint \--- \--- hint \--- Here are the code blocks you need to use: ![ghost-sprite](images/ghost-backdrop.png)

```blocks3
stop [all]

< [ ] = [ ] >

set [time v] to [10]

change [time v] by (-1)

(time)

wait (1) seconds

repeat until < >
end

when flag clicked

```

\--- /hint \--- \--- hint \--- Here is the code you should add to create a timer: ![backdrop icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

만약 게임이 너무 쉽다면 다음과 같이 바꿀 수 있습니다.

+ 플레이 시간을 줄여 보세요.
+ 유령이 덜 나타나게 바꿔 보세요.
+ 유령의 크기를 줄여 보세요.

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---