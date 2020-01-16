## Πρόσθεσε ένα χρονόμετρο

Τώρα θα προσθέσεις ένα χρονόμετρο έτσι ώστε ο παίκτης να έχει μόνο δέκα δευτερόλεπτα για να πιάσει όσο το δυνατόν περισσότερα φαντάσματα.

\--- task --

Δημιούργησε μία νέα μεταβλητή που ονομάζεται 'χρόνος'.

\--- /task \---

\--- task --

Μπορείς να προσθέσεις ένα χρονόμετρο στο Σκηνικό σου για να δώσεις στον παίκτη σου μόνο 10 δευτερόλεπτα για να πιάσει όσα περισσότερα φαντάσματα μπορεί;

Το χρονόμετρό σου πρέπει να:

+ Ξεκινά από τα 10 δευτερόλεπτα
+ Μειώνεται κάθε δευτερόλεπτο

Το παιχνίδι πρέπει να σταματά όταν το χρονόμετρο φτάσει στο 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![ghost-sprite](images/ghost-backdrop.png)

```blocks3
σταμάτησε [all]

< [ ] = [ ] >

όρισε [time v] σε [10]

άλλαξε [time v] κατά (-1)

(time)

περίμενε (1) δευτερόλεπτα

επανάλαβε ώσπου < >
end

Όταν στην πράσινη σημαία γίνει κλικ

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
Όταν στην πράσινη σημαία γίνει κλικ
όρισε [time v] σε [10]
επανάλαβε ώσπου <(time) = [0]> 
  περίμενε (1) δευτερόλεπτα
  άλλαξε [time v] κατά (-1)
end
σταμάτησε [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Δώσεις στον παίκτη λιγότερο χρόνο
+ Κάνεις τα φαντάσματα να εμφανίζονται λιγότερο συχνά
+ Κάνεις τα φαντάσματα μικρότερα

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---