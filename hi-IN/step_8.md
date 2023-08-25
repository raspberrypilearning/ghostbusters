## घड़ी जोड़ें

अब आप एक घड़ी जोड़ने जा रहे हैं ताकि खिलाड़ी के पास अधिक से अधिक भूतों को पकड़ने के लिए केवल दस सेकंड हो।

\--- task \---

'time' नामक एक नया वेरिएबल बनाएँ।

\--- /task \---

\--- task \---

क्या आप अपने खिलाड़ी को भूतों को पकड़ने के लिए केवल 10 सेकंड देने के लिए अपने स्टेज में एक घड़ी जोड़ सकते हैं?

आपकी घड़ी को चाहिए कि:

+ 10 सेकंड से शुरू करें
+ हर सेकंड को गिने

घड़ी के 0 पर पहुंचने पर खेल बंद हो जाना चाहिए।

\--- hints \--- \--- hint \---

जब हरा झंडा क्लिक किया गया हो `When the green flag is clicked`{:class="block3events"}, तो आपका `time`{:class="block3variables} वेरिएबल `set to 10`{:class="block3variables"} होना चाहिए। फिर इसे हर सेकंड `change by -1`{:class="block3variables"} हो जाना चाहिए जब तक यह 0 तक नहीं पहुंचे `until it reaches 0`{:class="block3control"}।

\--- /hint \--- \--- hint \---

आपको इन कोड ब्लॉक्स की ज़रुरत पड़ेगी:

![भूत स्प्राइट](images/ghost-backdrop.png)

```blocks3
stop [all]

< [ ] = [ ] >

set [time v] to [10]

change [time v] by (-1)

(time)

wait (1) seconds

repeat until < >
end

when flag clicked

```

\--- /hint \--- \--- hint \---

यहाँ वह कोड है जिसे आपको घड़ी बनाने के लिए जोड़ना चाहिए:

![बैकड्रॉप आइकन](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

अपने गेम को आज़माने के लिए किसी मित्र से कहें। वे कितने पॉइंट्स हासिल कर पाते हैं?

\--- /task \---

यदि आपका खेल बहुत आसान है, तो आप यह कर सकते हैं:

+ खिलाड़ी को कम समय दें सकते है
+ भूतों को कम बार प्रकट कर सकते हैं
+ भूतों को छोटा बना सकते है

\--- task \---

अपने गेम को तब तक बदलें और परखें जब तक कि आप इसके कठिनाई स्तर से खुश न हों।

\--- /task \---