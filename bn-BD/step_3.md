## এলোমেলো ভূত তৈরি করুন।

আপনার ভূতটি এই মুহুর্তে ধরা সত্যিই সহজ, কারণ এটি সরছে না!

\--- /task \---

আপনি কি নিজের ভূতে কোড যুক্ত করতে পারেন যাতে একই অবস্থানে থাকার পরিবর্তে ভূতটি স্টেজের এলোমেলো অবস্থানগুলিতে উপস্থিত হয়?

\--- hints \---

\--- hint \---

প্রতিবার আপনার ভূতটিকে এলোমেলো অবস্থানে প্রদর্শিত হওয়ার জন্যে এটা লিখুন `go to`{:class="block3motion"}

\--- /hint \--- \--- hint \---

এখানে কোড ব্লকের দুটি সেট রয়েছে যা আপনি ব্যবহার করতে পারেন। আপনার পছন্দসই সেটটি বেছে নিন।

![ghost-sprite](images/ghost-sprite.png)

হয় আপনার ভূত স্প্রাইট ব্লক এই সেটটি যোগ করুন:

```blocks3
go to (random position v)
```

বা এটি আপনার স্প্রাইটে যুক্ত করুন:

```blocks3
go to x: (14) y: (50)
pick random (1) to (10)
pick random (1) to (10)
```

\--- /hint \---

\--- hint \---

আপনার কোডটি হয় দেখতে এমনটি হওয়া উচিত:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

বা এটি এর মতো দেখতে পারে:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---