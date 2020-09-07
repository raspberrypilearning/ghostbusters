## ஒரு பேயை அசைவூட்டல்(animate) செய்யவும்

--- task ---

ஒரு புதிய வெற்று Scratch திட்டத்தைத் திறக்கவும்.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

ஒரு புதிய பேய்(ghost) sprite மற்றும் ஒரு பொருத்தமான மேடை பின்னணியை(stage backdrop) சேர்க்கவும்.

![திரைப்பிடிப்பு](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

பச்சைக் கொடியை கிளிக் செய்யும்போது, பேய் தோன்றி, பின் மறைவதை தொடர்ந்து செய்துகொண்டிருக்க வேண்டும். இதற்கான குறியீட்டை உங்கள் பேய் sprite-இல்(ஸ்ப்ரைட்) சேர்க்கவும்.

--- hints ---
 --- hint ---

பச்சைக் கொடி கிளிக் செய்யப்பட்டவுடன்(`green flag is clicked`{:class="block3events"}), உங்கள் பேய் ஒரு வினாடி(`one second`{:class="block3control"}) மறைய வேண்டும்(`hide`{:class="block3looks"}), பின்னர், அடுத்த ஒரு வினாடி(`one second`{:class="block3control"}) தோன்ற வேண்டும்(`show`{:class="block3looks"}). இதை எப்போதும்(`forever`{:class="block3control"}) தொடர்ச்சியாக செய்ய வேண்டும்.

--- /hint --- --- hint ---

உங்களுக்கு தேவையான குறியீட்டு தொகுதிகள்(code blocks) இங்கே:

![பேய்-sprite](images/ghost-sprite.png)

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

உங்கள் குறியீடு இவ்வாறு இருக்க வேண்டும்:

![பேய்-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint ---
--- /hints ---

--- /task ---

--- task ---

உங்கள் திட்டத்தை சோதித்து, பின் சேமிக்கவும்.

[[[generic-scratch3-saving]]]

--- /task ---