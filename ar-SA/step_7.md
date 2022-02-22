## التحدي: كائنات أخرى

والان سنجعل من لعبتك أكثر تشويقاً بتسجيل نقاط!

--- task ---

إنشاء متغير جديد يدعى`نتيجة`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ---

هل تستطيع تتبع نقاط الاعب؟ يجب أن يتمكن اللاعبين من إحراز النقاط عند النقر فوق الاشباح لاصطيادها.

في كل مرة ينقر فيها اللاعب على الشبح، يجب ان تزيد عدد النقاط.

![زيادة النقاط](images/ghost-score-test.png)

--- hints ---
 --- hint ---

`عند نقر العلم الاخضر`{:class="block3events"} فإن متغير `نتيجة`{:class="block3variables"} يجب أن `يساوي 0`{:class="block3variables"}. المنصة هي أفضل مكان لإضافة هذه التعليمة البرمجية.

`عند نقر كائن الشبح`{:class="block3events"} فان متغير `نتيجة`{:class="block3variables"} يجب أن `تتغير بمقدار 1`{:class="block3variables"}.

--- /hint --- --- hint ---

هنا التعليمات البرمجية التي ستحتاج اليها:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
set [نتيجة v] to (0)

when flag clicked
```

![كائن الشبح](images/ghost-sprite.png)

```blocks3
change [نتيجة v] by (1)
```

--- /hint --- --- hint ---

![أيقونة الخلفية](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [نتيجة v] to (0)
```

![كائن الشبح](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+ change [نتيجة v] by (1)
```

--- /hint ------ /hints ---

--- /task ---