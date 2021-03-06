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
به (موضع عشوائي v) برو
```

أو تضيف هذه المجموعة الى كائن الشبح:

```blocks3
به x: (14) و y: (50) برو

(انتخاب تصادفی از (1) تا (10))

(انتخاب تصادفی از (1) تا (10))
```

--- /hint ---

--- hint ---

يمكن أن تبدو التعليمات البرمجية خاصتك إما بهذا الشكل:

![كائن الشبح](images/ghost-sprite.png)

```blocks3
وقتی که پرچم کلیک شد
برای همیشه 
پنهان کن
(1) ثانیه صبر کن
به (موضع عشوائي v) برو
نمایش بده
(1) ثانیه صبر کن
end
```

أو يمكن أن تبدو بهذا الشكل:

![كائن الشبح](images/ghost-sprite.png)

```blocks3
وقتی که پرچم کلیک شد
برای همیشه 
پنهان کن
(1) ثانیه صبر کن
به x: (انتخاب تصادفی از (-150) تا (150)) و y: (انتخاب تصادفی از (-150) تا (150)) برو
نمایش بده
(1) ثانیه صبر کن
end
```

--- /hint ------ /hints ---

--- /task ---