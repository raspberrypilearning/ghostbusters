## 점수 추가하기

이제 점수 기능을 추가하여 게임을 더욱 재미있게 만들 것입니다!

\--- task \---

먼저, `score`{:class="block3variables"}라는 이름의 새 변수를 추가 해 보세요.

[[[generic-scratch3-add-variable]]]

\--- /task \---

\--- task \---

플레이어의 점수를 기록할 수 있나요? 플레이어는 유령을 잡을 때마다 점수를 얻어야 합니다.

플레이어가 유령을 클릭할 때마다 점수가 올라가야 합니다.

![점수 올리기](images/ghost-score-test.png)

\--- hints \--- \--- hint \---

`녹색 깃발이 클릭되면`{:class=”block3events”}, `점수`{:class=”block3variables”} 변수는 `0으로 정하기`{:class=”block3variables"}로 초기화 되어야 합니다.. 무대가 위의 코드를 추가하기 가장 합당한 곳이겠죠.

-`유령 스프라이트가 클릭되면`{:class=”block3events”}, `점수`{:class=”block3variables”} 변수는 `1만큼 변화하기`{:class=”block3variables"}를 사용하여 값이 변해야 합니다..

\--- /hint \--- \--- hint \---

Here are the code blocks you need:

![백드롭 아이콘](images/ghost-backdrop.png)

```blocks3
[score v] 를 (0) 로 정하기

flag 클릭했을 때
```

![유령 스프라이트](images/ghost-sprite.png)

```blocks3
[score v] 를 (1) 만큼 바꾸기
```

\--- /hint \--- \--- hint \---

![backdrop icon](images/ghost-backdrop.png)

```blocks3
flag 클릭했을 때
[score v] 를 (0) 으로 설정하기
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
이 스프라이트를 클릭했을 때
숨기기

+ [score v] 를 (1) 만큼 바꾸기
```

\--- /hint \--- \--- /hints \---

\--- /task \---