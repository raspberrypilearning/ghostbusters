## Σχεδιάζοντας ένα φάντασμα

\--- task --

Άνοιξε ένα νέο έργο στο Scratch.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task --

Πρόσθεσε ένα νέο αντικείμενο-φάντασμα και ένα κατάλληλο υπόβαθρο σκηνικού.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task --

Πρόσθεσε κώδικα στο χαρακτήρα φαντάσματος έτσι ώστε το φάντασμα να εμφανίζεται και να εξαφανίζεται για πάντα όταν πατηθεί η πράσινη σημαία.

\--- hints \--- \--- hint \---

Once the `green flag is clicked`{:class="block3events"}, your ghost should `hide`{:class="block3looks"} for `one second`{:class="block3control"} and then `show`{:class="block3looks"} for `one second`{:class="block3control"}. Θα χρειαστεί αυτό να γίνεται `για πάντα`{:class="blockcontrol"}. \--- /hint \--- \--- hint \---

Εδώ είναι τα μπλοκ που χρειάζεσαι:![ghost-sprite](images/ghost-sprite.png)

```blocks3
εξαφανίσου

εμφανίσου

για πάντα
end

περίμενε (1) δευτερόλεπτα

περίμενε (1) δευτερόλεπτα

Όταν στην πράσινη σημαία γίνει κλικ
```

\--- /hint \--- \--- hint \--- Έτσι πρέπει να μοιάζει με ο κώδικάς σου:![ghost-sprite](images/ghost-sprite.png)

```blocks3
Όταν στην πράσινη σημαία γίνει κλικ
για πάντα 
  εξαφανίσου
  περίμενε (1) δευτερόλεπτα
  εμφανίσου
  περίμενε (1) δευτερόλεπτα
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task --

Δοκίμασε και αποθήκευσε το έργο σου.

[[[generic-scratch3-saving]]]

\--- /task \---