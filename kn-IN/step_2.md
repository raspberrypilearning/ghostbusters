## ಭೂತವನ್ನು ಅನಿಮೇಟ್(Animate) ಮಾಡಿ

--- task ---

ಹೊಸ ಖಾಲಿ Scratch ಯೋಜನೆಯನ್ನು ತೆರೆಯಿರಿ.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

ಹೊಸ ghost sprite ಮತ್ತು ಸೂಕ್ತ ಹಂತದ ಹಿನ್ನೆಲೆಯನ್ನು ಸೇರಿಸಿ.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

ನಿಮ್ಮ ghost sprite ಗೆ ಕೋಡ್‌ ಸೇರಿಸಿ ಇದರಿಂದ ಹಸಿರು ಧ್ವಜವನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿದಾಗ ಭೂತ ಶಾಶ್ವತವಾಗಿ ಕಾಣಿಸಿಕೊಂಡು ಕಣ್ಮರೆಯಾಗುತ್ತದೆ.

--- hints ---
 --- hint ---

Once the `green flag is clicked`{:class="block3events"}, your ghost should `hide`{:class="block3looks"} for `one second`{:class="block3control"} and then `show`{:class="block3looks"} for `one second`{:class="block3control"}. ಇದನ್ನು `forever`{:class="block3control"} ಮಾಡಬೇಕಾಗಿದೆ.

--- /hint --- --- hint ---

ನಿಮಗೆ ಅಗತ್ಯವಿರುವ ಕೋಡ್ ಬ್ಲಾಕ್‌ಗಳು ಇಲ್ಲಿವೆ:

![ghost-sprite](images/ghost-sprite.png)

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

ನಿಮ್ಮ ಕೋಡ್ ಹೀಗಿರಬೇಕು:

![ghost-sprite](images/ghost-sprite.png)

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

ನಿಮ್ಮ ಯೋಜನೆಯನ್ನು ಪರೀಕ್ಷಿಸಿ ಮತ್ತು save ಮಾಡಿ.

[[[generic-scratch3-saving]]]

--- /task ---