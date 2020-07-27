---
layout: post
title: Happy birthday
subtitle: You already know coding, you just didn't realize!
gh-repo: gioele-santi/gioele_dev
gh-badge: []
tags: [coding, music]
comments: true
---

Coding is giving instructions to a computer to solve a problem or complete a task.

We can write more complex definitions and go deep with details but now I want to focus on what you already know.

The key is to take a **complex action** and subdivide it in a **series of simple actions**.

Simple actions are combined, repeated until the desired result is reached.

### Let's consider a song 

Lyrics are *instructions* that tell the singer what words (s)he should sing.
We can consider them as a **single block of text** but we all know that a song can be divided in smaller pieces: **chorus** end **verses**.

Chorus and verses are combined, sorted and repeated to create a whole song and then a perfomance (execution).

We know that the chorus can be repeated multiple times, so we don't need to rewrite it every time. We just need to reference it.

### I bet you know this one

Every child should know this classic song.

{% highlight javascript linenos %}
Happy birthday to you  
Happy birthday to you  
Happy birthday dear [name]  
Happy birthday to you
{% endhighlight %}

As you can see, lines 1, 2 and 4 are just repetitions of the chorus.  
So we could write it like this:

{% highlight javascript linenos %}
chorus:
    Happy birthday to you (x 2) 
verse:
    Happy birthday dear [name]  
chorus (x 1)
{% endhighlight %}

We have labelled the lyrics using **chorus** and **verse** and we also wrote repetitions.

One of the key points of coding is repeating an instruction multiple times.  
You see, you already know how to do that!

### Variable

*Happy birthday* is a peculiar song. Lyrics always fit, whoever is the person.
That's because we replace `[name]` with the actual name of the person. 

`[name]` is what we call a **variable**. It allows us generalize lyrics or a piece of code and reuse it in different situations.

This is just a first step, but realizing that the principles of coding are all around us, will be a great help in understanding the world of programming. 