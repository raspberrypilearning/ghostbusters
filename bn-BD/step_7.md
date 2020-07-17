## একটি স্কোর যোগ করুন

এখন আপনি স্কোর রেখে আপনার খেলাটিকে আরও আকর্ষণীয় করে তুলছেন!

\--- task \---

স্কোর নামে একটি নতুন ভেরিয়েবল তৈরি করুন `score`{:class="block3variables"}

[[[generic-scratch3-add-variable]]]

\--- task \---

\--- task \---

আপনি খেলোয়াড় এর স্কোর মনে রাখতে পারেন? খেলোয়াড়রা পয়েন্ট পাবেন যতবার তারা ভূতেদের ওপর ক্লিক করতে পারবেন|

প্রতিবার কোনও খেলোয়াড় ভূতে ক্লিক করলে, তাদের স্কোর বাড়ানো উচিত।

![ক্রমবর্ধমান স্কোর](images/ghost-score-test.png)

\--- hint \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `score`{:class="block3variables"} variable should be `set to 0`{:class="block3variables"}. এই কোডটি যুক্ত করার জন্য স্টেজটি সেরা জায়গা।

`When the ghost sprite is clicked`{:class="block3events"}, the `score`{:class="block3variables"} variable should be `changed by 1`{:class="block3variables"}.

\--- /hint \--- \--- hint \---

আপনার প্রয়োজনীয় কোডগুলি এখানে রইল:

![ব্যাকড্রপ আইকন](images/ghost-backdrop.png)

```blocks3
set [score v] to (0)

when flag clicked
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
change [score v] by (1)
```

\--- /hint \--- \--- hint \---

![ব্যাকড্রপ আইকন](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [score v] to (0)
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide

+ change [score v] by (1)
```

\--- /hint \--- \--- /hints \---

\--- /task \---