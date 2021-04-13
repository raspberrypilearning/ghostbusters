## यादृच्छिक भूत

याक्षणी आपले भूत पकडणे खरोखर सोपे आहे, कारण ते हालत नाही!

\--- task \---

आपण आपल्या भूतला कोड जोडू शकता जेणेकरून, त्याच स्थितीत राहण्याऐवजी, भूत स्टेजवरील यादृच्छिक स्थानांवर दिसून येईल?

\--- hints \---

\--- hint \---

प्रत्येक वेळी आपल्या भूत आधी दिसते काय, तो पाहिजे `जा`{वर्ग = "block3motion"} स्टेज वर एक यादृच्छिक स्थान.

\--- /hint \--- \--- hint \---

आपण येथे वापरू शकता असे कोड ब्लॉक्सचे दोन संच आहेत. आपल्याला पसंत असलेला सेट निवडा.

![भूत-स्प्राइट](images/ghost-sprite.png)

एकतर आपल्या गोस्ट स्प्राइटमध्ये ब्लॉक्सचा हा सेट जोडा:

```blocks3
वर जा (यादृच्छिक स्थिती v)
```

किंवा आपल्या स्प्राइटमध्ये हे जोडा:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

\--- /hint \---

\--- hint \---

आपला कोड यासारखे दिसू शकतो:

![भूत-स्प्राइट](images/ghost-sprite.png)

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

किंवा हे असे दिसू शकते:

![भूत-स्प्राइट](images/ghost-sprite.png)

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