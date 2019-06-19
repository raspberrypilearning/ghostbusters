## Ysbrydion ar hap

Mae dy ysbryd yn hawdd iawn i’w ddal ar hyn o bryd gan nad yw e’n symud!

\--- task \---

Alli di ychwanegu côd i dy ysbryd fel ei fod - yn hytrach nag aros mewn un man - yn ymddangos mewn manau ar hap ar y Llwyfan?

\--- hints \---

\--- hint \---

Bob tro mae dy ysbryd yn ymddangos, fe ddylai `fynd i`{:class="block3motion"} fan ar hap ar y Llwyfan.

\--- /hint \--- \--- hint \---

Mae dau set o flociau côd mae modd eu defnyddio yma. Dewisa'r rhai sydd well gyda ti.

![corlun-ysbryd](images/ghost-sprite.png)

Unai ychwanega'r blociau yma i gorlun dy ysbryd:

```blocks3
mynd i (random position v)
```

Neu yr un yma:

```blocks3
mynd i x: (14) y: (50)

(dewis ar hap (1) i (10))

(dewis ar hap (1) i (10))
```

\--- /hint \---

\--- hint \---

Fe allai dy gôd edrych fel hyn:

![corlun-ysbryd](images/ghost-sprite.png)

```blocks3
pan fo'r flag werdd yn cael ei glicio
am byth 
 cuddio
 aros (1) eiliad
 mynd i (random position v)
 dangos
 aros (1) eiliad
end
```

Neu fe allai edrych fel hyn:

![corlun-ysbryd](images/ghost-sprite.png)

```blocks3
pan fo'r flag werdd yn cael ei glicio
am byth 
 cuddio
 aros (1) eiliad
 mynd i x: (dewis ar hap (-150) i (150)) y: (dewis ar hap (-150) i (150))
 dangos
 aros (1) eiliad
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---