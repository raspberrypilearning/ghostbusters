## ಭೂತಗಳನ್ನು ಹಿಡಿಯುವ ಕೋಡ್

ಈಗ ನೀವು ನಿಮ್ಮ ಆಟಕ್ಕೆ ಕೋಡ್ ಸೇರಿಸಲು ಹೊರಟಿದ್ದೀರಿ ಆದ್ದರಿಂದ ಆಟಗಾರನು ಭೂತಗಳನ್ನು ಹಿಡಿಯಬಹುದು!

--- task ---

ನಿಮ್ಮ ಭೂತ ಸಿಕ್ಕಿಬಿದ್ದಾಗ ಅದನ್ನು ಕಣ್ಮರೆಯಾಗಿಸಬಹುದೇ? ಆಟಗಾರನು ಕ್ಲಿಕ್ ಮಾಡಿದಾಗ ಭೂತವನ್ನು ಹಿಡಿಯಲು ಸಾಧ್ಯವಾಗಬೇಕು.

ನಿಮ್ಮ ಆಟವನ್ನು ನೀವು ಪರೀಕ್ಷಿಸಿದಾಗ ಭೂತಗಳನ್ನು ಹಿಡಿಯುವುದು ಕಷ್ಟಕರವೆಂದು ಅನಿಸಿದರೆ, ಈ ಬಟನ್ನನ್ನು ಕ್ಲಿಕ್ ಮಾಡುವುದರ ಮೂಲಕ ನೀವು ಪೂರ್ಣ-ಪರದೆ ಮೋಡ್‌ನಲ್ಲಿ ಆಟವನ್ನು ಆಡಬಹುದು:

![screenshot](images/ghost-fullscreen-annotated.png)

--- hints ---
 --- hint ---

`When clicked`{:class="block3events"}, ನಿಮ್ಮ ghost sprite `hide`{:class="block3looks"} ಆಗಬೇಕು.

--- /hint --- --- hint ---

ನಿಮ್ಮ ಕೋಡ್ ಈ ರೀತಿ ಕಾಣಿಸಬೇಕು:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
when this sprite clicked
hide
```

--- /hint ------ /hints ---

--- /task ---