## ಟೈಮರ್ ಸೇರಿಸಿ

ಈಗ ನೀವು ಟೈಮರ್ ಅನ್ನು ಸೇರಿಸಲು ಹೊರಟಿದ್ದೀರಿ ಆದ್ದರಿಂದ ಆಟಗಾರನಿಗೆ ಸಾಧ್ಯವಾದಷ್ಟು ಭೂತಗಳನ್ನು ಹಿಡಿಯಲು ಕೇವಲ ಹತ್ತು ಸೆಕೆಂಡುಗಳು ಮಾತ್ರ ಇರುತ್ತವೆ.

--- task ---

'time' ಎಂಬ ಹೊಸ ವೇರಿಯೇಬಲ್ ಅನ್ನು ರಚಿಸಿ.

--- /task ---

--- task ---

ಭೂತಗಳನ್ನು ಹಿಡಿಯಲು ನಿಮ್ಮ ಆಟಗಾರನಿಗೆ ಕೇವಲ 10 ಸೆಕೆಂಡುಗಳನ್ನು ನೀಡಲು ನಿಮ್ಮ ಸ್ಟೇಜ್ ಗೆ ಟೈಮರ್ ಅನ್ನು ಸೇರಿಸಲು ಸಾಧ್ಯವೇ?

ನಿಮ್ಮ ಟೈಮರ್ ಹೀಗೆ ಮಾಡಬೇಕು:

+ 10 ಸೆಕೆಂಡುಗಳಲ್ಲಿ ಪ್ರಾರಂಭಿಸಬೇಕು
+ ಪ್ರತಿ ಸೆಕೆಂಡಗೆ ಏಣಿಕೆ ಮಾಡಿ

ಟೈಮರ್ 0 ಗೆ ಬಂದಾಗ ಆಟವು ನಿಲ್ಲಬೇಕು.

--- hints ---
 --- hint ---

`When the green flag is clicked`{:class="block3events"}, ನಿಮ್ಮ `time`{:class="block3variables"} ವೇರಿಯೇಬಲ್ ಅನ್ನು`set to 10`{:class="block3variables"} ಗೆ ಹೊಂದಿಸಬೇಕು. ನಂತರ ಪ್ರತಿ ಸೆಕೆಂಡ್ ಗೆ `changed by -1`{:class="block3variables"} `until it reaches 0`{:class="block3variables"} ಆಗಬೇಕು.

--- /hint --- --- hint ---

ನೀವು ಬಳಸಬೇಕಾದ ಕೋಡ್ ಬ್ಲಾಕ್‌ಗಳು ಇಲ್ಲಿವೆ:

![ghost-sprite](images/ghost-backdrop.png)

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

ಟೈಮರ್ ರಚಿಸಲು ನೀವು ಸೇರಿಸಬೇಕಾದ ಕೋಡ್ ಇಲ್ಲಿದೆ:

![backdrop icon](images/ghost-backdrop.png)

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

ನಿಮ್ಮ ಆಟವನ್ನು ಪರೀಕ್ಷಿಸಲು ಸ್ನೇಹಿತರನ್ನು ಕೇಳಿ. ಅವರು ಎಷ್ಟು ಅಂಕಗಳನ್ನು ಗಳಿಸಬಹುದು?

--- /task ---

ನಿಮ್ಮ ಆಟವು ತುಂಬಾ ಸುಲಭವಾಗಿದ್ದರೆ, ನೀವು ಹೀಗೆ ಮಾಡಬಹುದು:

+ ಆಟಗಾರನಿಗೆ ಕಡಿಮೆ ಸಮಯ ನೀಡಿ
+ ಭೂತಗಳು ಇನ್ನೂ ಕಡಿಮೆ ಬಾರಿ ಕಾಣುವಂತೆ ಮಾಡಿ
+ ಭೂತಗಳನ್ನ ಚಿಕ್ಕದಾಗಿಸಿ

--- task ---

ನಿಮ್ಮ ಆಟದ ಕಷ್ಟದ ಮಟ್ಟವನ್ನು ನಿಮಗೆ ಸಂತೋಷವಾಗುವವರೆಗೆ ಕೆಲವು ಬಾರಿ ಬದಲಾಯಿಸಿ ಮತ್ತು ಪರೀಕ್ಷಿಸಿ.

--- /task ---