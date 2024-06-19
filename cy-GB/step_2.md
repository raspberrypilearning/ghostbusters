## Animeiddio ysbryd

--- task ---

Agora brosiect Scratch gwag newydd.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Ychwanega gorlun ysbryd newydd a chefnlen addas i'r Llwyfan.

![sgrinlun](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Ychwanega gôd at dy gorlun ysbryd fel bod yr ysbryd yn ymddangos ac yn diflannu am byth pan fydd y faner werdd yn cael ei glicio.

--- hints ---
 --- hint ---

Unwaith mae'r `faner werdd wedi ei glicio`{:class="block3events"}, fe ddylai dy ysbryd `guddio`{:class="block3looks"} am `un eiliad`{:class="block3control"} yna `dangos`{:class="block3looks"} am `un eiliad`{:class="block3control"}. Mae angen iddo wneud hyn `am byth`{:class="block3control"}.
--- /hint ---
 --- hint ---

Dyma'r blociau côd rwyt ti eu hangen: ![corlun-ysbryd](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint --- --- hint --- Dyma sut dylai dy gôd edrych: ![corlun-ysbryd](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Profa ac arbed dy gôd.

[[[generic-scratch3-saving]]]

--- /task ---