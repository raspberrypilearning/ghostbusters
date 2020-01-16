## 유령 움직여 보기

\--- task \---

새 스크래치 프로젝트 만들기

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

새로운 유령 스프라이트를 추가하고 어울리는 배경을 넣으세요.

![스크린샷](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

유령이 나타났다 사라졌다는 반복하도록 코드를 추가해 보세요.

\--- hints \--- \--- hint \---

\--- hints \---\--- hint \---`녹색 깃발이 클릭되면`{:class=”blockevents”}, 유령을 `1초 동안`{:class=”blockcontrol”} `숨기기`{:class=”blocklooks”} 로 숨겼다가 `1초 동안`{:class=”blockcontrol”} `보이기`{:class=”blocklooks”} 로 보여줘야 합니다. 위의 작업을 `무한 반복하기`{:class=”blockcontrol”} 로 반복해 봅시다.

\--- /hint \--- \--- hint \---

Here are the code blocks you need:

![유령 스프라이트](images/ghost-sprite.png)

```blocks3
숨기기

보이기

무한 반복
끝

(1) 초 기다리기

(1) 초 기다리기

flag 클릭했을 때
```

\--- /hint \--- \--- hint \---

This is what your code should look like:

![유령 스프라이트](images/ghost-sprite.png)

```blocks3
flag 클릭했을 때
무한 반복
숨기기
(1) 초 기다리기
보이기
(1) 초 기다리기
끝
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Test and save your project.

[[[generic-scratch3-saving]]]

\--- /task \---