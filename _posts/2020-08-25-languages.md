---
layout: post
title: Languages
subtitle: Why the computer does not reply when you speak to it
cover-img: /assets/img/assembly_language.png
thumbnail-img: /assets/img/assembly_language.png
share-img: /assets/img/assembly_language.png
gh-repo: gioele-santi/gioele_dev
gh-badge: []
tags: [coding, programming, language]
comments: true
---

When we talked about pinning the tail on the donkey we said that coding consists in **telling instructions**, the problem is that the computer does not speak our language.

So what language does computer speak? Several I would say.  
The core of the computer, CPU (Central Processing Unit) uses **machine language** that is a small set of **simple instructions**, written as numbers (binary numbers eg: 00101001).

**Assembly** is another language, basically it matches **each machine language instruction** with a **short word**, making it more *understandable* for a human (eg: MOV, SUM).

### Low level language, high level language

Assembly is more understandable but yet very difficult to use, even for an expert programmer as to perform very complex operations, it is necessary to combine many of these simple instructions, sometimes reaching a very high level of complexity. 

That's because this language is very **close to the inner workings of the processor**. So it is called **low level language**, but please do not be fooled by the name, it has no negative or dismissive meaning on the contrary low level languages are very important and hard to master.

The solution that computer scientists figured out was to **invent another language** (actually more than one) that could be **even easier** to use.
These new languages are known as **high level languages** and they are closer to human language. 

### Powerful words

Such languages have **more instructions** and they are even more complex or as we usually say **more powerful**. That means that **a single instruction** in an high level language corresponds to **many instructions** in a lower one.

Let's consider a powerful word: *multiply*.  
Why is it powerful? Why is it an *higher level instruction*?

{: .box-note}
5 x 8 = 5 + 5 + 5 + 5 + 5 + 5 + 5 + 5

Multiplication means repeating several times the same addition. That's actually what a processor would do: loop several times through a series of additions (*repeat* and *sum* are two basic low level operations).

### Translation

The use of higher level languages is allowed by special programs called **translators** (intepreters and compilers) that take higher level instructions and turn them into lower ones.

Applying multiple levels of translation allows more layers of programming languages that can get near to human language and make programming even easier and powerful. But that is for another post.
