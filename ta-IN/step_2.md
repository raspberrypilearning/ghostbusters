## ஒரு பேயை அசைவூட்டல்(animate) செய்யவும்

\--- task \---

Open a new empty Scratch project by [clicking here](https://scratch.mit.edu/projects/editor/).

\--- /task \---

\--- task \---

Delete the cat sprite by clicking on the bin icon over the sprite thumbnail. ![The image depicts a thumbnail in the Scratch programming interface. It shows the orange Scratch Cat mascot, which is the default sprite for Scratch projects, displayed in a purple-bordered square labeled "Sprite1." There is also a trash can icon with a white "X" in the top-right corner of the thumbnail, indicating the option to delete the sprite.](images/scratch-thumbnail.png)

\--- /task \---

\--- task \---

ஒரு புதிய பேய்(ghost) sprite மற்றும் ஒரு பொருத்தமான மேடை பின்னணியை(stage backdrop) சேர்க்கவும்.

![The image depicts a stylized blue ghost-like character with spots, standing in a dark, eerie forest. The forest features leafless trees with slender, bare branches and a purple and black background, suggesting a nighttime setting. The moon is partially visible in the top-left corner, adding to the spooky atmosphere.](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

பச்சைக் கொடியை கிளிக் செய்யும்போது, பேய் தோன்றி, பின் மறைவதை தொடர்ந்து செய்துகொண்டிருக்க வேண்டும். இதற்கான குறியீட்டை உங்கள் பேய் sprite-இல்(ஸ்ப்ரைட்) சேர்க்கவும்.

![The image shows a small, cartoonish blue ghost-like figure with rounded edges and a translucent appearance. It has a single, large, black mouth on its left side, a few darker blue spots scattered across its body, and a dripping effect at the bottom, giving it a liquid-like texture.](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

\--- /task \---

\--- task \---

Test and save your project. You should see the ghost appear and disappear when you click the green flag.

[[[generic-scratch3-saving]]]

\--- /task \---