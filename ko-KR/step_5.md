## 유령을 잡아볼까요

이제 플레이어가 유령을 잡을 수 있도록 게임에 코드를 추가 할 것입니다!

--- task ---

유령이 붙잡 혔을 때 사라지게 할 수 있습니까? 플레이어는 유령을 클릭하여 잡을 수 있어야 합니다.

게임을 테스트해보고 유령을 잡는 것이 어렵다면 이 버튼을 클릭하여 전체 화면 모드로 게임을 즐길 수 있습니다:

![스크린샷](images/ghost-fullscreen-annotated.png)

--- hints ---
 --- hint ---

`클릭`{:class=”blockevents”}하면, 유령 스프라이트는 `숨기기`{:class=”blocklooks"} 상태가 되어야 합니다..

--- /hint --- --- hint ---

다음과 같은 코드가 될 것입니다.:![유령 스프라이트](images/ghost-sprite.png)

```blocks3
이 스프라이트를 클릭했을 때
숨기기
```

--- /hint --- --- /hints ---

--- /task ---