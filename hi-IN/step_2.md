## भूत का एनीमेशन बनाना

\--- task \---

एक नया खाली Scratch प्रोजेक्ट खोलें।

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

एक नया भूत स्प्राइट और एक उपयुक्त पृष्ठभूमि (backdrop) स्टेज में जोड़ें।

![स्क्रीनशॉट](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

अपने भूत स्प्राइट में कोड जोड़ें ताकि हरे झंडे पर क्लिक करने पर भूत हमेशा के लिए प्रकट होता और गायब होता रहे।

\--- hints \--- \--- hint \---

जब आप `green flag is clicked`{:class="block3events"}, तब आपका भूत `hide`{:class="block3looks"} `one second`{:class="block3control"} के लिए चाहिए और फिर `show`{:class="block3looks"} `one second`{:class="block3control"} के लिए चाहिए। इसको यह कार्य `forever`{:class="block3control"} के लिए करना हैं।

\--- /hint \--- \--- hint \---

आपको इन कोड ब्लॉक्स की ज़रुरत पड़ेगी:

![भूत स्प्राइट](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

\--- /hint \--- \--- hint \---

आपका कोड ऐसा दिखना चाहिए:

![भूत स्प्राइट](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

अपने प्रोजेक्ट को जाँच कर सेव कर लीजिये।

[[[generic-scratch3-saving]]]

\--- /task \---