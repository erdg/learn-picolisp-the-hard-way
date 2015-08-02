# Exercise 1: Welcome to the REPL

At your command line, type
```bash
$ pil +
:
```
A happy little colon should appear, awaiting any questions you might have about PicoLisp.

But first things first. What the heck is a 'REPL', anyway? It stands for Read Evaluate Print Loop. That's a fancy way of saying that PicoLisp is going to look at what you type, do something with it, show you the result, and then wait for you to type something else.

So let's get typing!
```lisp
: 15    # type '15' and hit 'enter'
-> 15
: 16
-> 16
: 23457890
-> 23457890
```
Numbers! My favorite! But... what's going on here? I like to think of it as having a little conversation with PicoLisp. PicoLisp is pretty shy, however, and will only talk to you if you ask questions. Pretty one-sided. And PicoLisp really only likes to talk about itself. It's a computer program though, so we can excuse the slight social awkwardness. The `:` is PicoLisp's way of letting you know that its ready for your next question; the answer is anything that follows the `->`. The above example thus becomes a little conversation,

> "Hey PicoLisp, what's `15`?"
>
> "I know that! `15` is the numeral `15`. It looks like this!"

Fascinating.

You may not know it yet, but PicoLisp is going to become a great friend. Be patient. As with any blossoming friendship, you have to trudge through the necessary small talk. As you become more comfortable with one another, you'll both start to open up and have deeper conversations. Hiding behind that cold colon is a real softie who wants to hear all about your hopes, dreams, greatest fears, and aspirations. But PicoLisp would never tell you that directly.

And so we ask questions.
```lisp
: (+ 1 2)
-> 3
: (- 4 2)
-> 2
```
What?! Oh yeah, I forgot to mention that PicoLisp is pretty particular about how you ask questions. If it's a multipart question (e.g. "can you add 1 and 2?") you have to close the whole question in parentheses, so PicoLisp knows that it all belongs together. And why does the plus sign come first? Who *does* that?! Again, PicoLisp is picky. It wants to know what it will be doing, *before* it knows what it will be doing it to. The above example thus becomes,

> "Hey PicoLisp, get ready to add numbers"
>
> "Alright, I'm ready. What numbers would you like me to add?"
>
> "The numbers `1` and `2`"
>
> "Easy peasy, bro. That be `3`."

It takes a little getting used to, for sure. But it turns out to be pretty slick. Instead of writing,
```lisp
: (1 + 2 + 3 + 4 + 5 + 6)  # PicoLisp will get mad if you ask this
-> can u rephrase that, plz? k thx. 
```
We can just write,
```lisp
: (+ 1 2 3 4 5 6)
-> 21
```
PicoLisp FTW! 


