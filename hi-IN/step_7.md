## स्कोर जोड़ें

चलिए स्कोर रखकर इसे और भी दिलचस्प बनाएँ!

--- task ---

`score`{:class="block3variables"} नामक वेरिएबल बनाएँ।

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ---

क्या आप खिलाड़ी के स्कोर का ध्यान रख सकते हैं? स्कोर बनाने के खिलाड़ी को भूत पकड़ने के लिए उन पर क्लिक करना होगा।

हर बार खिलाड़ी भूत पर क्लिक करें, तो उनके स्कोर बढ़ने चाहिए।

![स्कोर बढ़ाना](images/ghost-score-test.png)

--- hints ---
 --- hint ---

जब हरा झंडा क्लिक किया गया हो `When the green flag is clicked`{:class="block3events"}, तो आपका `score`{:class="block3variables"} वेरिएबल `set to 0`{:class="block3variables"} होना चाहिए। इस कोड को जोड़ने के लिए स्टेज सबसे बढ़िया स्थान है।

भूत स्प्राईट को क्लिक करने पर `When the ghost sprite is clicked`{:class="block3events"}, तो `score`{:class="block3variables"} वरियबल को `changed by 1`{:class="block3variables"} हो जाना चाहिए।

--- /hint --- --- hint ---

आपको इस कोड ब्लॉक की ज़रुरत पड़ेगी:

![बैकड्रॉप आइकन](images/ghost-backdrop.png)

```blocks3
set [score v] to (0)

when flag clicked
```

![भूत स्प्राइट](images/ghost-sprite.png)

```blocks3
change [score v] by (1)
```

--- /hint --- --- hint ---

![बैकड्रॉप आइकन](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [score v] to (0)
```

![भूत स्प्राइट](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+ change [score v] by (1)
```

--- /hint ------ /hints ---

--- /task ---