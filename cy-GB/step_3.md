## Ysbrydion ar hap

Mae dy ysbryd yn hawdd iawn i’w ddal ar hyn o bryd gan nad yw e’n symud!

--- task ---

Alli di ychwanegu côd i dy ysbryd fel ei fod - yn hytrach nag aros mewn un man - yn ymddangos mewn manau ar hap ar y Llwyfan?

--- hints ---


--- hint ---

Bob tro mae dy ysbryd yn ymddangos, fe ddylai `fynd i`{:class="block3motion"} fan ar hap ar y Llwyfan.

--- /hint --- --- hint ---

Mae dau set o flociau côd mae modd eu defnyddio yma. Dewisa'r rhai sydd well gyda ti.

![corlun-ysbryd](images/ghost-sprite.png)

Unai ychwanega'r blociau yma i gorlun dy ysbryd:

```blocks3
go to (safle ar hap v)
```

Neu yr un yma:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

Fe allai dy gôd edrych fel hyn:

![corlun-ysbryd](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (safle ar hap v)
show
wait (1) seconds
end
```

Neu fe allai edrych fel hyn:

![corlun-ysbryd](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---