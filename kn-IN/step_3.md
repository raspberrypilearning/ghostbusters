## Random ಭೂತಗಳು

ನಿಮ್ಮ ಭೂತವನ್ನು ಈ ಸಮಯದಲ್ಲಿ ಹಿಡಿಯಲು ಬಹಳ ಸುಲಭವಾಗಿದೆ, ಏಕೆಂದರೆ ಅದು ಚಲಿಸುತ್ತಿಲ್ಲ!

--- task ---

ನಿಮ್ಮ ಭೂತಕ್ಕೆ ನೀವು ಕೋಡ್ ಅನ್ನು ಸೇರಿಸಬಹುದೇ, ಅದೇ ಸ್ಥಾನದಲ್ಲಿ ಉಳಿಯುವ ಬದಲು, ವೇದಿಕೆಯಲ್ಲಿ random ಸ್ಥಾನಗಳಲ್ಲಿ ಭೂತ ಕಾಣಿಸಿಕೊಳ್ಳುತ್ತದೆ?

--- hints ---


--- hint ---

ಪ್ರತಿ ಬಾರಿ ನಿಮ್ಮ ಭೂತ ಕಾಣಿಸಿಕೊಳ್ಳುವ ಮೊದಲು, ಅದು ವೇದಿಕೆಯ ಮೇಲೆ random ಸ್ಥಾನಕ್ಕೆ `go to`{:class="block3motion"} ಆಗಬೇಕು.

--- /hint --- --- hint ---

ನೀವು ಇಲ್ಲಿ ಬಳಸಬಹುದಾದ ಎರಡು ಸೆಟ್ ಕೋಡ್ ಬ್ಲಾಕ್‌ಗಳಿವೆ. ನೀವು ಬಯಸಿದ ಸೆಟ್ ಅನ್ನು ಆರಿಸಿ.

![ghost-sprite](images/ghost-sprite.png)

ನಿಮ್ಮ ghost sprite ಗೆ ಈ ಬ್ಲಾಕ್‌ಗಳ ಗುಂಪನ್ನು ಸೇರಿಸಿ:

```blocks3
go to (random position v)
```

ಅಥವಾ ಇದನ್ನು ನಿಮ್ಮ sprite ಗೆ ಸೇರಿಸಿ:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

ನಿಮ್ಮ ಕೋಡ್ ಈ ರೀತಿ ಕಾಣಿಸಬಹುದು:

![ghost-sprite](images/ghost-sprite.png)

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

ಅಥವಾ ಇದು ಈ ರೀತಿ ಕಾಣಿಸಬಹುದು:

![ghost-sprite](images/ghost-sprite.png)

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

--- /hint ------ /hints ---

--- /task ---