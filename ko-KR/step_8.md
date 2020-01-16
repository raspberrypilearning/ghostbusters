## 타이머 추가하기

이제 플레이어가 유령을 잡을 수 있는 시간을 10초로 제한하도록 타이머를 추가할 것입니다.

\--- task \---

'시간'이라는 새 변수를 추가합니다.

\--- /task \---

\--- task \---

무대에 타이머를 추가해서 플레이어가 10초 동안만 유령을 잡게 만들 수 있나요?

타이머는 이렇게 동작해야 해요.

+ 10초부터 시작합니다.
+ 매 초 숫자가 줄어듭니다.

타이머가 0이 되면 게임이 끝나야 합니다.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![유령 스프라이트](images/ghost-backdrop.png)

```blocks3
정지 [all]

< [ ] = [ ] >

[time v] 를 [10] 로 정하기

[time v] 를 (-1) 만큼 바꾸기

(time)

(1) 초 기다리기

반복하기 < >
끝

flag 클릭했을 때

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![백드롭 아이콘](images/ghost-backdrop.png)

```blocks3
flag 클릭했을 때
[time v] 를 [10] 로 정하기
< (time) = [0] > 까지 반복하기
(1) 초 기다리기
[time v] 를 (-1) 만큼 바꾸기
끝
정지 [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ 플레이 시간을 줄여 보세요.
+ 유령이 나타나는 회수를 줄여 보세요.
+ 유령의 크기를 줄여 보세요.

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---