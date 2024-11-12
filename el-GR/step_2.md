## Σχεδιάζοντας ένα φάντασμα

--- task ---

Άνοιξε ένα νέο έργο στο Scratch.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Πρόσθεσε ένα νέο αντικείμενο-φάντασμα και ένα κατάλληλο υπόβαθρο σκηνικού.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Πρόσθεσε κώδικα στο χαρακτήρα φαντάσματος έτσι ώστε το φάντασμα να εμφανίζεται και να εξαφανίζεται για πάντα όταν πατηθεί η πράσινη σημαία.

--- hints ---
 --- hint ---

Μόλις `πατηθεί η πράσινη σημαία`{:class="blockevents"}, θα πρέπει να `εξαφανίζεται`{:class="blocklooks"} το φάντασμά σου για `ένα δευτερόλεπτο`{:class="blockcontrol"} και στη συνέχεια να `εμφανίζεται`{:class="blocklooks"} για `ένα δευτερόλεπτο`{:class="blockcontrol"}. Θα χρειαστεί αυτό να γίνεται `για πάντα`{:class="blockcontrol"}.
--- /hint ---
 --- hint ---

Αυτά είναι τα μπλοκ κώδικα που θα χρειαστείς:

![αντικείμενο-φάντασμα](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint --- --- hint --- Έτσι πρέπει να μοιάζει ο κώδικάς σου:

![αντικείμενο-φάντασμα](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Δοκίμασε και αποθήκευσε το έργο σου.

[[[generic-scratch3-saving]]]

--- /task ---