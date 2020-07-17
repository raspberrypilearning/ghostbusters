## একটি প্রাণবন্ত ভূত তৈরি করুন

\--- /task \---

একটি নতুন খালি Scratch প্রকল্প খুলুন।

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- /task \---

একটি নতুন ভূত স্প্রাইট এবং একটি উপযুক্ত স্টেজ ব্যাকড্রপ যোগ করুন।

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- /task \---

আপনার ভূত স্প্রাইটে কোড যোগ করুন যাতে ভূতটি প্রদর্শিত হয় এবং সবুজ পতাকা ক্লিক করার সময় চিরতরে অদৃশ্য হয়ে যায়।

\--- hints \--- \--- hint \---

Once the `green flag is clicked`{:class="block3events"}, your ghost should `hide`{:class="block3looks"} for `one second`{:class="block3control"} and then `show`{:class="block3looks"} for `one second`{:class="block3control"} এটি চিরদিনের জন্য করতে হলে লিখুন `forever`{:class="block3control"}

\--- /hint \--- \--- hint \---

আপনার প্রয়োজনীয় কোডগুলি এখানে রইল:

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

\--- /hint \--- \--- hint \---

আপনার কোডটি দেখতে এমন হওয়া উচিত:

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

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- /task \---

আপনার কোডটি পরীক্ষা করুন এবং সংরক্ষণ করুন।.

[[[generic-scratch3-saving]]]

\--- /task \---