+++
title = "My long awaited post malloc update post!"
date = 2025-11-06
+++

Hello from the other side! I spent a considerable amount of the time between October and now
working on two labs: these were malloclab and tshlab. As the name may suggest, in malloclab,
we have to implement a memory allocator. In tshlab, we have to implement a simple linux
shell. 

# Malloc
I have undoubtedly spent the plurality of my time these past few weeks implementing
`malloc`. Malloc is a great assignment for a systems class, as it lets you explore a
rich program design space where implementation decisions you make can have a great
deal of influence on the benchmarks of your program. 

## A brief overview
Why should someone implement `malloc`? What does implementing `malloc` do? First, 
if we read the question as asking "what function does malloc serve", the answer is
that we obtain a way of writing data structures of arbitrary or variable size by 
"allocating" memory in a region called the heap. "Well libc already has malloc, and
it's Production Grade so...": have you considered that learning and trying things is 
good for you?

What is difficult about implementing malloc? You have no variable-size data structures! 
(Technically you have a GCC extension width 0 array in our implementation, but shhhhhh.....)
You have to do everything via variables you store on the stack. Also, debugging utilities like
gdb do not provide nearly as much help as they do on other comparable systems labs, so 
you end up having to do a lot of checking and generally have to have airtight implementation.
I would talk more about this, but if I did that this would be less of a blog post and more of a
summary of a lab handout, at which point you'd be better off taking the class instead :P

# Model Theory
I have also been spending a lot of time theseweeks on a DRP (Directed Reading Program) in which I meet
weekly with a graduate student mentor and we talk about Model Theory. In the broadest possible sense,
Model Theory is about the study of objects which capture a certain set of true statements generated
by various symbols (which together are called a language). There are a lot of neat things you can 
do by studying various notions of constructing models, relationships between models and the statements
contained within them, but I will wait for another time to talk about all of this.

# Next Semester...
Not learning from my past mistakes, I decided to challenge myself again with a record 3 CS courseload 
next semester. (On the bright side, this is it. I am not taking any other non-StuCo class!) I am by far
the most excited about 15-411: Compiler Design and Implementation. This is sure to be by a considerable
margin the most intense class, estimated at around 22-25 hours/week if FCE data is to be trusted. Also,
I GET TO USE RUST!!!! :D and I am taking it with another furry! I genuinely like the content, I am very
eager to do work on making several compilers and entering into this really neat area of study. The second
class, one which I am also quite excited for, is 15-312: Foundations of Programming Languages. This is a
class that I know many people become obsessed with and fell down the Type Theory/PL pipeline because of, 
if they hadn't already by taking 15-150. I have for a long time now wanted to explore the abstract/structural 
properties of programming languages as systems because it tickles my brain in the same way that my interest
in Logic does (at the very least so I can better understand what Lean is doing). The last (and least exciting)
is 15-210 Parallel and Sequential DSA, which I don't know what to expect from. I have heard very mixed
things about it, but I am taking it with many friends so this will help me out with the material at any
rate.

More importantly however, I will have no life or free time!! (again :3) so if I disappear off the face of the
earth, this is why! I should have another update coming after I go ride lots of trains once the semester ends :)

Take care!

Aured
+++
title: "Planning my panel"
date: 2025-06-01
+++

I was recently informed that the panel proposal I submitted for this year's
Anthrocon has been accepted. Great! After the last two years, I am happy that 
the panel is going to be official this time and I can't wait to see what the 
turnout is like.

On the subject of the panel, I have thoughts about what I want to talk about. 
As of June 1st, I am the only Pittsburgh resident on the panel. As such, I know a lot of
operational things about the system and would be the best equipped to explain its 
usage. Aside from 
this, I am contemplating writing about some of Pittsburgh's history
to illustrate how transit evolved to its current form.

It definitely hasn't escaped my mind that a lot of transit enthusiasts are prone 
to uninformed conjecture and speculation about transit proposals and general 
malaise about "the state of transit." I think idealism and dreams are very 
valuable for inspiring people to pursue a course of action, but there is a point
where you can be led astray by your ideals and create an enemy out of the good in
pursuit of the perfect. 

I want to somehow impart in my presentation that so many of the operational 
decisions a transit agency makes are a result of myriad circumstances coming 
together. "Replace this bus with a streetcar" and "extend the T to the airport 
now!" are good dreams, but I want people to ask themselves if the realization
of a dream is worth the costs it has elsewhere. We all have to live in the world 
of optimizing finite resources because we aren't 
[Robert Moses](https://en.wikipedia.org/wiki/Robert_Moses) and 
don't have the level of power needed to enact our will directly into stone, so we 
should do our best to operate within it.

I will update my site with more information about my presentation in the coming 
weeks. I hope anyone who goes to Anthrocon stops by if they have any interest in 
walkable cities, cyclable cities, and vibrant urban spaces that afford their 
residents opportunity and the joy of being among people. 

Excited to see you there :)
