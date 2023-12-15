# Performance-aware programming

## What is Performance-aware programming?
When we talk about "performance-aware programming" we often think of "Optimization".
We now, for a fact, that the terms can be related and almost identical, but....
When I say "Performance-aware programming" I'm not referring to all of those complex
techniques you need to know about, in order to do the thing called "Optimization".

Basically, when I'm talking about "Performance-aware programming", I'm just referring
to the fact of "being totally/more aware of how the CPU receives and handles/process"
every instruction that we **write in our code**.

This is very important because now people only think about "Optimizing" their code
but they don't get fact that maybe..... only maybe, they don't even need to get to
that point. Maybe, the only thing they need to do is to be **more aware** of: **How
am I asking the **CPU** to handle each **instruction**?**

## Vague diagram on how the CPU works (but it is enough by now :D)
```
                  4.2ghz
                |--------|
  Intruction    |        |   Completes Instruction
------------->  |  CPU   | ------------------------->
                |        |
                |--------|

```
Yeap... It is a very simple/vague diagram on what the CPU does with the instructions
it gets (basically process them and complete each of them). The idea is clear! :D

## Why this diagram is helpul?
Because I can now explain to you that the only **TWO** things, yeap you read it right!
The only two things we need, to improve the performance of our programs are:

    1. Reduce the # of instructions
    2. Increase the speed in which each instruction is processed by the CPU

### "This is crazy" you may think! :D
I got you.... I thoguht the same at the beggining, but the thing is that, even if there
are only "two steps" to improve the performance of our programs, in reality, this two
steps can be approached in **MULTIPLE WAYS**. That is the heart of this course! :P
