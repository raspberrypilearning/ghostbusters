## Animate a ghost

--- task ---

Open a new empty Scratch project.

[[[generic-scratch-new-project]]]

--- /task ---

--- task ---

Add in a new ghost sprite and a suitable Stage backdrop.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch-sprite-from-library]]]

[[[generic-scratch-backdrop-from-library]]]

--- /task ---

--- task ---

Add code to your ghost sprite so that the ghost appears and disappears forever when the green flag is clicked.

--- hints ---
--- hint ---

Once the `green flag is clicked`{:class="blockevents"}, your ghost should `hide`{:class="blocklooks"} for `one second`{:class="blockcontrol"} and then `show`{:class="blocklooks"} for `one second`{:class="blockcontrol"}. It needs to do this `forever`{:class="blockcontrol"}.
--- /hint ---
--- hint ---

Here are the code blocks you need:
![ghost-sprite](images/ghost-sprite.png)
```blocks
hide

show

forever
end

wait (1) secs

wait (1) secs

when flag clicked
```
--- /hint ---
--- hint ---
This is what your code should look like:
![ghost-sprite](images/ghost-sprite.png)
``` blocks
when flag clicked
forever
hide
wait (1) secs
show
wait (1) secs
end
```
--- /hint ---
--- /hints ---

--- /task ---

--- task ---

Test and save your project.

[[[generic-scratch-saving]]]

--- /task ---
