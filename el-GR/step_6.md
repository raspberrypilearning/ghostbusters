## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Το χρονόμετρό σου πρέπει να:

+ Ξεκινά από τα 10 δευτερόλεπτα
+ Μειώνεται κάθε δευτερόλεπτο

Το παιχνίδι πρέπει να σταματά όταν το χρονόμετρο φτάσει στο 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![εικονίδιο φόντου](images/ghost-backdrop.png)

```blocks3
Όταν στην πράσινη σημαία γίνει κλικ
όρισε [time v] σε [10]
επανάλαβε ώσπου <(time) = [0]> 
  περίμενε (1) δευτερόλεπτα
  άλλαξε [time v] κατά (-1)
end
σταμάτησε [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Άλλαξε και δοκίμασε το παιχνίδι σου μερικές φορές μέχρι να είσαι ευχαριστημένος ότι είναι το σωστό επίπεδο δυσκολίας.

\--- /task \---