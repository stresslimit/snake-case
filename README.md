# The Case for Snake Case

We strongly prefer working with snake_case over camelCase, and always use snake when we have a choice. And, we want to provide others with the power to make this same choice, against mountains of opposition.


## The Case

### More Readable

A [reddit thread](http://www.reddit.com/r/ruby/comments/1fsopk/ruby_vindicated_eyetracking_study_finds_that/) about an [eye-tracking study finds snake_case easier to read](http://www.cs.kent.edu/~jmaletic/papers/ICPC2010-CamelCaseUnderScoreClouds.pdf)


### Less Confusion

Consider a variable or function containing the ID of an object; let's say "get the id". In camelCase there are many ways to do this, which can be hard to remember:

- getId
- getID

In snake_case it's clear:

- get_id


## The Case Against

### It's the JavaScript Way

Just cause we've always done something a certain way doesn't mean we shouldn't change. The current convention is actually a kind of [skeuomorphism](http://en.wikipedia.org/wiki/Skeuomorph) [which is officially "uncool" on the internet], where older constraints to reduce character count in code was relevant. If you really want to save characters you will certainly be pre-parsing to uglify your code.


### It's harder to type

Use your pinky!! Or make a shortcut to make Shift+Space make you an underscore. Or use a code editor/IDE that prompts you so you don't have to type the full variable/function name anyway.


## Fallen Heros

These projects have valiantly tried to implement a snake_case syntax, but eventually caved to common pressure:

- meteor.js
- coffeescript


## Resources

We will provide the following resources:

- mini javascript lib that prototypes all native javascript API functions into their snake equivalents
- textmate bundle or mac snippet that creates the shortcut "Shift + Spacebar" that enters an underscore 

