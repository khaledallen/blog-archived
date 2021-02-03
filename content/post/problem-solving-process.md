---
title: "Problem Solving Process"
date: 2021-02-03T10:36:29-07:00
draft: true
---

I've been preparing for a coding interview recently, and as a result
I have given a lot of thought to how I tend to solve problems.

When I started back in to school, I didn't have a great problem-solving
process. I had always been "the smart kid" and didn't need
to do anything special that I was aware of in order to solve most of the
problems I encountered. The only exception to that was some of the very
difficult games I like to play. Persistence was my friend in those cases,
as well as a very developed sense of the metagame.

---

_**metagaming** is using the fact that you are
playing a game to help overcome its challenges. Games have certain norms
and assumptions. For example, there is a way to defeat every enemy. It
follows that if you are stuck on a boss, it's either because you haven't
found **the** way to defeat it, or you aren't executing well._

_In other contexts, metagaming tells you that a solution exists because
the problem is being presenting in an artificial fashion. For example, in
tutoring ACT/SAT, I tell students that every question has a correct answer
and the test will tell you what that answer is, if you know where to
look._

_In theory, it does not help with naturally occurring problems. In
practice, I've never encountered a time when assuming a solution existed
wasn't helpful, as long as that assumption is checked at some point._

---

When I started studying mathematics, this didn't work. So I started
developing an explicit problem-solving process, much of it coming from my
work as a tutor teaching students how to crack the ACT and SAT tests.

Roughly, it is:

1. Spend some time with the problem 
2. "What would make this easy?" 
3. Make it like something familiar 
4. Make it concrete
5. Test
6. Look for shortcuts and refine

## Spend some time with the problem: seek first to understand

the story that encapsulates this is one about Einstein (probably false).
It is said that, when asked what he would do if given 1 hour to solve
a world-ending problem, he responded that he would spend 50 minutes
understanding the problem, and 10 minutes applying his solution.

For me, understanding a problem feels a like the sensation I get when
I take something apart and put it back together again, like when I used to
build LEGOs as a kid. I would touch all the pieces, even the ones I didn't
need to, in order to understand how the model was constructed. I know I've
spent enough time on this when I have that mental sensation I had as a kid
that I could mostly build this model from scratch without the
instructions.

And, as I tell my students, if the problem seems confusing, go back and
spend more time understanding it. There is no point in trying to solve
a problem you don't understand, since you may not even solve the right
problem.

*Pay attention to your internal "sense of understanding."*

## What would make this easy to solve?

This is my favorite question to ask is, along with its cousin *"What about
this problem would need to be changed to make it trivial?"*

These are useful questions because many problems we encounter are just
more complicated versions of simpler problems we already know how to
solve. This question identifies the aspect of the new problem that makes
it new, so we can address it and get back to familiar territory.

But sometimes we really are dealing with a problem that we haven't seen
before. Then the answer to that question often becomes, "It woud be easy
if it were similar to something I've seen before," which naturally leads
to...

## How can we make this like something we've seen before

One of the  most common tools in math is to frame a new problem as an old
problem by looking for ways to associate new concepts with old ones.

A familiar version of this occurs in high school math. Coordinate geometry
is the hybrid of algebra and geometry. It lets us convert a line (which is
a spatial object) into an equation, _y=mx+b_, (which is a numerical
object) and work some magic on the numbers. Once we get what we need,we
convert it back into a picture. Much more tractable.

The point is that _y=mx+b_ is not just a line. It is a function, and it is
also useful for describing sequences where each term has a common
difference, and many other things. And *that* in turn suggests that we can
think of lines as sequences, or vice versa. And so on.

## Make it concrete

Actually describing a solution itself is part of solving a problem. I almost
didn't include this, because generating the solution itself isn't necessarily
something I used to think about, but there's a difference between saying, "Just
convert the line into an equation and calculate its slope, then convert it back
and draw it on the coordinate plane," and actually providing the process for
doing that. The process will reveal gaps in your understanding of the nature of
the problem.

It's like having an idea and writing it down (see the home page for my
thoughts on that).

## Test the solution

Walk through what I've come up with. In mathematics, I would step through my
proofs looking for assumptions or logical gaps. In programming, I step through
the code with a sample input (honestly, sometimes I just run it and see what
happens, but that's usually a sign it's time for a break). In building things,
I stop to imagine what it will do in the physical world before committing to
a prototype print.

## Refine

Once I have a rough solution, I go back and refine it, which itself is
a process. The first solution is rarely the most efficient, but it helped me
understand what's going on. Usually, I can remove mental scaffolds that aren't
really part of the solution but which helped me get there.

1. What worked? Why? Can it be combined with something else or consolidated?
2. What didn't work? Why? Do I need that? Can we bypass the problem entirely?
3. What should be changed to improve? Is that feasible?
4. Repeat with a smaller version of the big cycle.

This is essentially iterating. To refer back to the LEGOs, I often built
many versions of the thing I was aiming for. Each iteration was cleaner
and more structurally sound. Sometimes, I realized I was using too many
pieces, and sometimes I'd find a better piece later on from a new set.

Mentally, I am often much more explicit about the steps to a solution than
I need to be. Once I get to the solution, I backtrack and see which ideas
are truly needed to get to the solution, and which were just helpful to
understand it.

The goal is to have in mind a streamlined process encapsulated in a few
core concepts. Until I get here, I don't really consider the problem
"solved," just "addressed."

It's the difference between "beating" a game once, and "completing" it,
where the movements, attacks, timing, etc. is fluid and sure.

## Example: Coding Problems

My process is

1. Understand Requirements (Understand the problem)
2. Specify Input/Output (understand the problem)
3. Question assumptions (understand and what would make this easy)
4. Think and explore solutions (applying what woudl make this easy and is this
   like something I've seen before) 
5. Describe an implementation (make it concrete) 
6. Walk through the implementation with sample input (test)
6. Implement in code (make it concrete, test and refine)

Steps 3-6 get cycled, occasionally revisiting 1 and 2.

Notice, even here, the process of understanding takes us a huge amount of my
time spent on a problem. The actual implementing will take a lot of time by
virtue of the context, and within that, there will be many smaller problems
where I repeat the cycle.

## Example: Engineering Problem

My process for designing a widget to solve a problem with my 3D printer is

1. Specify the requirements. That is, what do I need this widget to do
   (Understand the problem)
2. Scope the problem. What *don't I need it do*? (Understand) 
3. See what's been done before (Understand and what woudl make this easy, is
   this like something familiar)
3. Sketch a solution (Understand the problem and what would make this easy,
   make it concrete) 
4. Design a print (make it concrete) 
5. Print and apply (make it concrete, test and refine) 
6. Repeat 3-5 (test and refine, unless things are really not working, then go
   back to 1)

I'm still new to engineering mindset, so I'm sure this process will get cleaned
up a lot. But when I started, I would just jump into a CAD and produce garbage.
Now I spend more time measuring, sketching, and scoping.
