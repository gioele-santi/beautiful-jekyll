---
layout: post
title: Pin the tail on the donkey
subtitle: Turn a kids' game into a coding experience
cover-img: /assets/img/Pin_the_Tail_On_the_Donkey-example.jpg
thumbnail-img: /assets/img/Pin_the_Tail_On_the_Donkey-example.jpg
share-img: /assets/img/Pin_the_Tail_On_the_Donkey-example.jpg
tags: [coding, game]
---

A problem and a simple set of instructions to solve it. A good starting point for a game but also for coding.  
One of the two players is **blindfolded** and must pin a paper tail in the right place. He can do only few actions: go **up**, **down**, **left** or **right** and finally **pin** the tail.  
The other player can see the drawing and must help giving **instructions**.

### Let's compare with computers

A computer is **dumb** and can do a limited set of actions. You may think your computer or smartphone is very powerful but the core is still a poor *dumb* processor moving bits and making sums.

The only way to make a computer work is giving it instructions. So programmers must use the set of available actions and combine them in different ways thus making more complex actions.

### Playing the game

When kids play the game, they freely move the tail in front of the drawing and unknowingly add some extra *commands*, like **stop** or **go on**.  
These extra commands are actually a way to communicate to the blindfolded kid that an action must be **repated until** a certain **condition** is reached.

So we know the concept of **loop**. Let's make an example, but to make it undestandable we have to use a grid made of squares. It will also make it compatible with computers later.

|   	| A 	| B 	| C 	| D 	| E 	| F 	| G 	| H 	|
|---	|---	|---	|---	|---	|---	|---	|---	|---	|
| 1 	| T 	|   	|   	|   	|   	|   	|   	|   	|
| 2 	|   	|   	|   	|   	|   	|   	|   	|   	|
| 3 	|   	|   	|   	|   	|   	|   D 	|   	|   	|
| 4 	|   	|   	|   	|   	|   	|   	|   	|   	|
| 5 	|   	|   	|   	|   	|   	|   	|   	|   	|

At the beginning Tail (T) is in position **(A,1)** while the Donkey's back (D) is in position **(F,3)**.  
The commands for the blindfolded player will be: **right**, **right**, **right**, **right**, **right**, **down**, **down**.

But we can also **generalize** these commands, we just have to think about what happens in the mind of the observer:
{% highlight javascript linenos %}
if D is on the right of T:
    while D is on the right:
        move T to the right
else if D is on the left of T:
    while D is on the left:
        move T to the left
if D is below T:
    while D is below:
        move T down
else if D is above T:
    while D is above:
        move T up
{% endhighlight %}

As you can see this is not a solution to a single problem, but it is a **generic approach** that can be used **for any position of T and D**.

If you think about it, we can rewrite the same instructions in much less lines, but optimization deserves a whole chapter on its own.


[Image from WikiMedia Commons](https://commons.wikimedia.org/wiki/File:Pin_the_Tail_On_the_Donkey-example.jpg)