## 유령 움직여 보기

\--- task \---

새 스크래치 프로젝트 만들기

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Add in a new ghost sprite and a suitable Stage backdrop.

![스크린샷](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Add code to your ghost sprite so that the ghost appears and disappears forever when the green flag is clicked.

\--- hints \--- \--- hint \---

Once the `green flag is clicked`{:class="block3events"}, your ghost should `hide`{:class="block3looks"} for `one second`{:class="block3control"} and then `show`{:class="block3looks"} for `one second`{:class="block3control"}. It needs to do this `forever`{:class="block3control"}. \--- /hint \--- \--- hint \---

Here are the code blocks you need: ![ghost-sprite](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

\--- /hint \--- \--- hint \--- This is what your code should look like: ![ghost-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

프로젝트를 테스트해 보고 저장하세요.

[[[generic-scratch3-saving]]]

\--- /task \---