## ஒரு நேரங்காட்டியைச் சேர்க்கவும்

இப்போது நீங்கள் ஒரு நேரங்காட்டியைச்(timer) சேர்க்கப் போகிறீர்கள், இதனால் விளையாடுபவருக்கு, முடிந்தவரை பல பேய்களைப் பிடிக்க பத்து வினாடிகள் மட்டுமே இருக்கும்.

--- task ---

'Time'(நேரம்) என்ற புதிய மாறியை உருவாக்கவும்.

--- /task ---

--- task ---

பேய்களைப் பிடிக்க விளையாடுபவருக்கு 10 வினாடிகள் மட்டுமே கொடுக்க, உங்கள் மேடையில்(stage) ஒரு நேரங்காட்டியைச் சேர்க்க முடியுமா?

உங்கள் நேரங்காட்டி பின்வருமாறு:

+ 10 வினாடிகளில் தொடங்க வேண்டும்
+ ஒவ்வொரு நொடியும் பின்னோக்கி எண்ண வேண்டும்(count down)

நேரங்காட்டி 0-க்கு வரும்போது விளையாட்டு நிறுத்தப்பட வேண்டும்.

--- hints ---
 --- hint ---

பச்சைக் கொடியைக் கிளிக் செய்யும் போது(`When the green flag is clicked`{:class="block3events"}), உங்கள் `time`{:class="block3variables"} மாறி, 10-ஆக அமைக்கப்பட வேண்டும்(`set to 10`{:class="block3variables"}). அது 0-ஐ அடையும் வரை(`until it reaches 0`{:class="block3control"}), ஒவ்வொரு நொடியும், -1 ஆல் மாற வேண்டும் (`change by -1`{:class="block3variables"}).

--- /hint --- --- hint ---

உங்களுக்கு தேவையான குறியீட்டு தொகுதிகள் இங்கே:

![பேய்-sprite](images/ghost-backdrop.png)

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

நேரங்காட்டியை உருவாக்க நீங்கள் சேர்க்க வேண்டிய குறியீடு இங்கே:

![பின்னணி icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

--- /hint ---
--- /hints ---

--- /task ---

--- task ---

உங்கள் நண்பரிடம், உங்கள் விளையாட்டை சோதிக்கச் சொல்லிக் கேளுங்கள். அவர்கள் எத்தனை புள்ளிகளைப் பெற முடியும்?

--- /task ---

உங்கள் விளையாட்டு மிகவும் எளிதானது என்றால், நீங்கள் பின்வருமாறு செய்யலாம்:

+ வீரருக்கு குறைந்த நேரம் கொடுங்கள்
+ பேய்கள் அடிக்கடி தோன்றுவதைக் குறையுங்கள்
+ பேய்களை சிறியதாக்குங்கள்

--- task ---

உங்கள் விளையாட்டின் கடின அளவில்(difficulty level) நீங்கள் திருப்தி அடையும்வரை, உங்கள் விளையாட்டை சில முறை மாற்றி மாற்றி, சோதித்துப் பாருங்கள்.

--- /task ---