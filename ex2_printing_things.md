# Exercise 2 - Printing Things

Welcome. Have you done Exercise 1 yet? Go back and do it again. 

```lisp
: (print hey)
NIL-> NIL
``` 
Hey! I asked you to print 'hey'. What gives?
```lisp
: (print 'hey)
hey-> hey
```

That's better. Notice any differences between the last two questions? The second 'hey' has a single quote character, `'`. Now, forget that ever happened.

```lisp 
: (print "Yo dawg, what's poppin'?")
"Yo dawg, what's poppin'?"-> "Yo dawg, what's poppin'?"
: (print "That's weird...")
"That's weird..."-> "That's weird..."
: (print "Why does PicoLisp print everything twice?")
"Why does PicoLisp print everything twice?"-> "Why does PicoLisp print everything twice?"
```

> "My good friend, would you be able to print something for me?"
>
> "Most certainly. What shall I print?"
> 
> "Just print 'hey'."
>
> "As you wish. I have printed 'hey'." The first 'hey' appears on your screen. "Oh, and by the way, the answer to your question is 'hey'." The second 'hey' comes up after the `->`.
>
> "Ahh... thanks PicoLisp."

When you ask PicoLisp to do something, sometimes it will do things that have an effect on the outside world. That just happened! You asked PicoLisp to print something to the screen. And so it was, and then PicoLisp answered your question. And the answer happened to be what you told it to print. Make sense? Of course not. PicoLisp is a strange being. More questions.

```lisp
: (print "What a strange world to live in...")
"What a strange world to live in..."-> "What a strange world to live in..."
: (print "trapped inside a computer.")
"trapped inside a computer."-> "trapped inside a computer."
: (print "I wonder what computers dream about.")
"I wonder what computers dream about."-> "I wonder what computers dream about."
: (print "Do they have a favorite video game?")
"Do they have a favorite video game?"-> "Do they have a favorite video game?"
: (print "I have a favorite video game!")
"I have a favorite video game!"-> "I have a favorite video game!"
```

Careful now, type this one exactly as I have.
```lisp
: (print "Hello, PicoLisp)
```
> "Ummm... PicoLisp? You there?" It's quite... quiet. *Too* quiet. You mash the keys and hit enter a couple times.
```lisp
: (print "Hello, PicoLisp)
obegcrki
pdyt
kjb
```
Nothing. Better call back later. Hit `ctrl-x` to end the call.
```lisp
: (print "Hello, PicoLisp)
obegcrki
pdyt
kjb   # hits `ctrl-x`

: 
```
Oh snap, He's back! If you ever get disconnected, hit `ctrl-x` to hang up and call back. That will usually work. 
