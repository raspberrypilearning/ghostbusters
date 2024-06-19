## Προσθήκη βαθμολογίας

Τώρα πρόκειται να κάνεις το παιχνίδι σου πιο ενδιαφέρον, διατηρώντας το σκορ!

--- task ---

Δημιούργησε μία νέα μεταβλητή με όνομα `σκορ`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ---

Μπορείς να παρακολουθείς τη βαθμολογία του παίκτη; Οι παίκτες πρέπει να κερδίζουν πόντους όταν πιάνουν φαντάσματα κάνοντας κλικ πάνω τους.

Κάθε φορά που ένας παίκτης κάνει κλικ σε ένα φάντασμα, η βαθμολογία πρέπει να αυξάνεται.

![Αυξάνοντας τη βαθμολογία](images/ghost-score-test.png)

--- hints ---
 --- hint ---

`Όταν πατηθεί η πράσινη σημαία`{:class="blockevents"}, η μεταβλητή σου `σκορ`{:class="block3variables"} πρέπει να `οριστεί σε 0`{:class="block3variables"}. Το Σκηνικό (Stage) είναι το καλύτερο μέρος για να προσθέσεις αυτόν τον κώδικα.

`Όταν πατηθεί η πράσινη σημαία`{:class="blockevents"}, η μεταβλητή σου `σκορ`{:class="block3variables"} πρέπει να `αλλάξει κατά 1`{:class="block3variables"}.

--- /hint --- --- hint --- Εδώ είναι τα μπλοκ που θα χρειαστείς:![backdrop icon](images/ghost-backdrop.png)

```blocks3
set [σκορ v] to (0)

when flag clicked
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
change [σκορ v] by (1)
```

--- /hint --- --- hint --- ![backdrop icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [σκορ v] to (0)
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+ change [σκορ v] by (1)
```

--- /hint --- --- /hints ---

--- /task ---