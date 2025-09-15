## أشباح عشوائية

في الوقت الراهن، من السهل جدًا اصطياد الشبح الخاص بك لأنه لا يتحرك!

--- task ---

هل تستطيع اضافة تعليمة برمجية الى كائن الشبح بحيث يظهر الشبح في مواقع عشوائية من المنصة بدلاً من البقاء في الموقع نفسه؟

--- hints ---


--- hint ---

في كل مرة قبل ظهور الشبح، يجب أن `يذهب الى`{:class="block3motion"}مكان عشوائي على المنصة.

--- /hint --- 
--- hint ---

هناك مجموعتين من التعليمات البرمجية التي بامكانك استخدامها هنا. اختر المجموعة التي تفضلها.

![كائن الشبح](images/ghost-sprite.png)

إما أن تضيف هذه المجموعة من القوائم الى كائن الشبح:

```blocks3
go to (random position v)
```

أو تضيف هذه المجموعة الى كائن الشبح:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

يمكن أن تبدو التعليمات البرمجية خاصتك إما بهذا الشكل:

![كائن الشبح](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

أو يمكن أن تبدو بهذا الشكل:

![كائن الشبح](images/ghost-sprite.png)

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

--- /hint ------ /hints ---

--- /task ---