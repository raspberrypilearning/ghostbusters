## أضف مؤقت

والان ستقوم باضافة مؤقت بحيث لا يتوفر للاعب سوى 10 ثواني لاصطياد أكبر عدد ممكن من الاشباح.

--- task ---

أنشئ متغيرًا جديدًا يُسمى 'الوقت'.

--- /task ---

--- task ---

هل تستطيع إضافة مؤقت الى المنصة لتمنح اللاعب 10 ثواني لاصطياد الاشباح؟

يجب برمجة الموقِت على النحو التالي:

+ يبدأ العد من 10 ثوان
+ يبدأ في العد التنازلي بمقدار ثانية واحدة

ستنتهي اللعبة عندما يصل الموقِت إلى 0.

--- hints ---
 --- hint ---

`عند نقر العلم الاخضر`{:class="block3events"} فإن متغير `الوقت`{:class="block3variables"} يجب أن `يساوي 10`{:class="block3variables"}. ثم `يتغير بمقدار -1`{:class="block3variables"} كل ثانية `حتى يصل الى 0`{:class="block3control"}.

--- /hint --- --- hint ---

هنا التعليمات البرمجية التي ستحتاج اليها:

![كائن الشبح](images/ghost-backdrop.png)

```blocks3
توقف [الكل]

<[ ] = [ ]>

[الوقت v] را به [10] تنظیم کن

مقدار [الوقت v] را (-1) تا تغییر بده

(الوقت)

(1) ثانیه صبر کن

تا وقتی که <> تکرار کن
end

وقتی که پرچم کلیک شد
```

--- /hint --- --- hint ---

إليك التعليمات البرمجية التي عليك إضافتها لإنشاء مؤقت:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
وقتی که پرچم کلیک شد
[الوقت v] را به [10] تنظیم کن
تا وقتی که <(الوقت) = [0]> تکرار کن 
(1) ثانیه صبر کن
مقدار [الوقت v] را (-1) تا تغییر بده
end
توقف [الكل]
```

--- /hint ------ /hints ---

--- /task ---

--- task ---

إسال صديقك لاختبار لعبتك. كم نقطة ممكن أن يسجلوا؟

--- /task ---

إذا كانت اللعبة سهلة للغاية، فيمكنك:

+ منح اللاعب وقتًا أقل
+ اجعل ظهور الأشباح أقل
+ تصغير أحجام الأشباح

--- task ---

غيِّر واختبر لعبتك عدد من المرات حتى تصل إلى مستوى الصعوبة الذي تريده.

--- /task ---