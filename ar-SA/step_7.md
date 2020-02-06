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
[نتيجة v] را به (0) تنظیم کن

وقتی که پرچم کلیک شد
```

![كائن الشبح](images/ghost-sprite.png)

```blocks3
مقدار [نتيجة v] را (1) تا تغییر بده
```

--- /hint --- --- hint ---

![أيقونة الخلفية](images/ghost-backdrop.png)

```blocks3
وقتی که پرچم کلیک شد
[نتيجة v] را به (0) تنظیم کن
```

![كائن الشبح](images/ghost-sprite.png)

```blocks3
وقتی که این شکلک کلیک شد
پنهان کن
+ مقدار [نتيجة v] را (1) تا تغییر بده
```

--- /hint ------ /hints ---

--- /task ---