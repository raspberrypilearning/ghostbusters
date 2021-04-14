## एक भूत आत्मसात करा

--- task ---

एक नवीन रिक्त स्क्रॅच प्रोजेक्ट उघडा.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

नवीन घोस्ट स्प्राइट आणि योग्य स्टेज पार्श्वभूमीवर जोडा.

![स्क्रीनशॉट](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

आपल्या भुताच्या स्प्राइटमध्ये कोड जोडा जेणेकरून हिरवा ध्वज क्लिक केला की भूत दिसून येईल आणि कायमचे अदृश्य होईल.

--- hints ---
 --- hint ---

एकदा `हिरवा झेंडा क्लिक केले आहे (green flag clicked)`{:class="block3events"}, आपल्या भूत पाहिजे `लपवा (hide)`{:class="block3looks"} साठी `एक सेकंद (one second)`{:class="block3control"} आणि नंतर `शो (show)`{:class="block3looks"} `एक सेकंद (one second)`{:class="block3control"} साठी. हे `कायमचे (forever)`{:class="block3control"} करणे आवश्यक आहे.

--- /hint --- --- hint ---

आपल्याला आवश्यक असलेले कोड ब्लॉक येथे आहेत:

![भूत-स्प्राइट](images/ghost-sprite.png)

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

आपला कोड यासारखा दिसला पाहिजे:

![भूत-स्प्राइट](images/ghost-sprite.png)

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

आपला प्रकल्पाची चाचणी घ्या आणि जतन करा.

[[[generic-scratch3-saving]]]

--- /task ---