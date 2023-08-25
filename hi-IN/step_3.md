## यादृच्छिक (random) भूत

आपका भूत इस समय पकड़ने में बहुत आसान है, क्योंकि यह चलता नहीं है!

\--- task \---

क्या आप अपने भूत में कोड जोड़ सकते हैं, ताकि एक ही स्थिति में रहने के बजाय, यह स्क्रीन पर यादृच्छिक स्थानों पर दिखाई दे?

\--- hints \---

\--- hint \---

हर बार आपका भूत आपके सामने नज़र आने से पहले, उसे `go to`{:class="block3motion"} ब्लॉक से स्टेज के किसी भी यादृच्छिक स्थान पर जाना चाहिए।

\--- /hint \--- \--- hint \---

यहाँ आप दो अलग कोड ब्लॉक्स का इस्तेमाल कर सकते है। इनमें से कोई एक, जो भी आपको ज़्यादा पसंद आये, चुन लीजिये।

![भूत स्प्राइट](images/ghost-sprite.png)

या तो नीचे दिए गए कोड को आपके भूत स्प्राइट के साथ जोड़ लीजिये:

```blocks3
go to (random position v)
```

नहीं तो यह कोड आपके स्प्राइट के साथ जोड़ लीजिये:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

\--- /hint \---

\--- hint \---

या तो आपका कोड ऐसा दिख सकता हैं:

![भूत स्प्राइट](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

या फिर ऐसा भी दिख सकता हैं:

![भूत स्प्राइट](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---