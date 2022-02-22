## تحريك شبح

--- task ---

افتح مشروع Scratch جديدًا وفارغًا.

[[[generic-scratch3-new-project]]]

---/task---

--- task ---

أضف كائن شبح جديد وخلفية مناسبة.

![لقطة الشاشة](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

---/task---

--- task ---

أضف تعليمة برمجية إلى كائن الشبح بحيث يظهر ويختفي باستمرار عندما تنقر فوق العلم الاخضر.

--- hints ---
 --- hint ---

بمجرد النقر فوق `العلم الاخضر`{:class="block3events"}، ستحتاج الى `اخفاء`{:class="block3looks"} الشبح لمدة `ثانية واحدة`{:class="block3control"} ثم `تظهره`{:class="block3looks"} لمدة `ثانية واحدة`{:class="block3control"}. ستحتاج أن تقوم بهذا `الى الابد`{:class="block3control"}.

--- /hint --- --- hint ---

هنا التعليمات البرمجية التي ستحتاج اليها:

![كائن الشبح](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint --- --- hint ---

و هذا ما يجب أن تبدو عليه التعليمات البرمجية الخاصة بك:

![كائن الشبح](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint ------ /hints ---

--- /task ---

--- task ---

إختبر واحفظ المشروع الخاص بك.

[[[generic-scratch3-saving]]]

--- /task ---