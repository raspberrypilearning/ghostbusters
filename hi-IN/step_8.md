## टाइमर(timer) जोड़ना

अब आप एक टाइमर जोड़ेंगे ताकि हर खिलाड़ी भूत पकड़ने के लिए अधिकतम 10 सेकंड का समय इस्तेमाल कर सकता हैं।

--- task ---

'time' नामक एक नया वेरिएबल बनाएँ।

--- /task ---

--- task ---

अपने खिलाड़ी को भूत पकड़ने के लिए अधिकतम 10 सेकंड का समय देने के लिए क्या आप अपनी स्टेज में टाइमर जोड़ सकते हैं?

आपके टाइमर को चाहिए कि:

+ 10 सेकंड से शुरू करें
+ हर सेकंड को गिने

जब टाइमर 0 हो जाए तो गेम को रुकना चाहिए।

--- hints ---
 --- hint ---

जब हरा झंडा क्लिक किया गया हो `When the green flag is clicked`{:class="block3events"}, तो आपका `time`{:class="block3variables"} वेरिएबल `set to 10`{:class="block3variables"} होना चाहिए। फिर इसे हर सेकंड `change by -1`{:class="block3variables"} हो जाना चाहिए जब तक यह 0 तक नहीं पहुंचे `until it reaches 0`{:class="block3control"} है।

--- /hint --- --- hint ---

आपको इन कोड ब्लॉक की ज़रुरत पड़ेगी:

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

--- /hint --- --- hint ---

यहाँ वह कोड है जिसे आपको टाइमर बनाने के लिए जोड़ना चाहिए:

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

--- /hint ------ /hints ---

--- /task ---

--- task ---

अपनी गेम का परीक्षण करने के लिए अपने मित्र से कहिए। वे कितने पॉइंट्स हासिल कर पाते हैं?

--- /task ---

यदि आपका गेम बहुत आसान है, तो आप यह कर सकते हैं:

+ खिलाड़ी को कम समय दें सकते है
+ भूत को कम बार प्रकट कर सकते है
+ भूत को छोटा बना सकते है

--- task ---

गेम में तब तक परिवर्तन करें और परीक्षण करें जब तक आप इसकी कठिनता के स्तर से ख़ुश न हो जाएँ।

--- /task ---