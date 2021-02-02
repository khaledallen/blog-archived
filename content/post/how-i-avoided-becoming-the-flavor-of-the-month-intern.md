---
layout: post
title: How I Avoided Becoming the Flavor-of-the-Month Intern
date: 2020-12-20
---

Last year, I had the amazing opportunity to intern at a NASA center. They
were looking for someone with JavaScript experience to update a data
collections tool that had been underutilized because it was not searchable
and had a poor UI. The plan was to rebuild it with a shiny new graph-based
database and to update the frontend to use React. Basically, modernize it
and clean it up.

All this was what my supervisors and their bosses wanted. They lacked the
time to build it, so they had requested me, the intern.

Unfortunately, when I arrived and we started moving on the project, the
technology provider for our department had other ideas. We were told that,
while we were welcome to build the tool with whatever technology stack we
wanted to, they could not support anything other than .NET.

I wanted to make a lasting impact, which meant providing something that
would stick around and improve people's lives for some time. If I forced
them to learn something new, they wouldn't. They just didn't have the time
to do that (that's why they hired me in the first place). If nobody knew
or cared about what I'd created, there would be no reason to support it
anyway. I needed to accomplish three things:

1. I needed to create something that could be easily integrated into
   existing systems and expertise.

2. I needed to get other people outside our team excited about the project
   so that they would want it, and therefore dedicate time and resources
   to keeping it around.

3. I needed to make myself replaceable, so that the software was not
   dependent on my presence and could be supported, extended, and used by
   anyone, without me around.

## Create something easily integrated

The guy in charge of the technology team supporting us told me about all
the past interns who had come in with new technologies and cutting edge
industry ideas, built excellent and shiny tools to solve everyone's
problems, and then gone home, leaving him with a product he couldn't
support. The tool would fall by the wayside and things would go back to
the way that they had been.

I faced a dilemma. I didn't know how to code in C#, much less build an
entire .NET content management system from the ground up, including
everything from user authentication and login up to records customization
and even a comment and notifications system. I didn't even know C# syntax
or conventions!

But if I stuck with JavaScript, I would leave them with a non-solution.
Someone would have to support my app after I went home, and the contractor
NASA had for that team was trained in .NET.

Sure, I could argue that the internet had moved on and they needed to
update their practices, but that attitude was denying the reality of their
restrictions. My priority was to solve a problem, to help the team that
had hired me, not to impress anyone with my JS chops and shiny new
technology. If that meant using a clunky .NET server-side app, that would
be the way to go. I buckled down, found a good .NET Core tutorial, and
spent the first two weeks of my internship teaching myself how to create
a .NET Core web app, using as close to industry best-practices as I could
discern.

I made sure to work closely with the support contractor whenever I found
myself making a decision about something they would need to interact with,
and I tried to anticipate ways that users would expect to be able to
configure the software.

I did the latter as I earned buy in from others outside our office.

## Earning Buy In

The tool I was asked to fix was one that everyone was familiar with
because they were required to use it. It was also one that nobody liked
using. The rationale behind the tool was appreciated, and most people
agreed that a skillful execution would be invaluable to them as
individuals and to the center as a whole.

Thus, when I came by asking what they would like to see in such
a renovation, people were excited to talk to me. I asked for specifics
regarding what they would like to do with such a tool and what they wanted
it to do for them.

Then, I built as much of those requests into the design as I could. I even
added "attachement points" in the code for features that weren't in the
core request from my supervisor, but which a lot of the folks
I interviewed seemed to want. These later proved useful because after
I finished the core of the product, I was able to expand it to serve
a whole new set of use cases. I also made it possible to turn on and off
these bells and whistles so that the same software could fill as many
roles as possible.

The other aspect of my conversations with people on center was to get as
many people as I could to feel a sense of ownership of the software I was
building.

## Making myself replaceable

I didn't want to be irreplaceable, because I would be leaving and if my
software depended on me being there, it wouldn't last very long. From the
very beginning, I tried to get others invested in the project. If not the
software specifically, then in what we were trying to do as a whole.
I worked to build a team of advocates, partly to have a wide base of
support, but also to distribute the emotional and mental burden of being
an advocate.

At the end of the project, I put a ton of time into documenting not just
the code, but also the ways to configure and use the software. I also
didn't just go off of what _I_ thought needed to be documented and
explained. I would have other people use it and let me know where they got
confused or stuck. Once I helped them out, I would add the explanation to
the README (or sometimes make a change to the software to make it more
intuitive).

I can't say I was as successful in this as the other goals I had for the
project. People at NASA just have a lot on their plates. But I do know
that my replacement has been successful and that many others on center at
least know about what we have built.

## Summary: Focus on helping others, from devs to users

All this worked. My internship was extended from 4 months to 12 so that
I had the opportunity to extend the software to ensure it was fully stable
and ready to be deployed into a production environment, with all the
features that had been requested. I also had the chance to extend it into
a more general tool which was deployed by another office for two of their
own projects. My succesor has reported that he has found the code easy to
understand (after a learning/training period) and to support. It's the
biggest thing I've built, and I had the opportunity to really dive into it
thanks to focusing on making it useful and usable for as many people as
I could.

I've even had people tell me explicitly I was the first person to provide
a solution that actually stuck and addressed a problem that had been
plaguing them for years, which several interns had attacked without much
success. I feel like a lot of what enabled me to be successful is the
organizational momentum built up by previous interns, but I was happy to
know I had provided that final push that broke through the barriers
holding back progress.

I hadn't really considered the support team to be users in the past. I had
always sort of figured that they were there to enable whatever tools the
real users wanted to use. But in this case, they held a lot of
decision-making power. That's a lesson I will take with me to my future
projects; even if they didn't have that formal power, they will always
have the ability to drag their feet and increase the friction of an
organization.

And then there is the next team of developers who take over my work. They
will need to find the tool easy to work with or else they might want to
build something themselves (which I'd be okay with except it just costs
the organization time and resources in the long run). So yeah, devs are
users too.

I learned a lot from a technical standpoint on that project, but at the
end of the day, it wasn't really that bad to learn .NET. I already
understood most of the rationale behind the way .NET was set up, since
most JS frameworks and stacks do the same job. I just had to learn some
new paths and syntax. Much more valuable were the human lessons I learned
about focusing on _all_ the users and building something that would be
easy to support, extend, and utilize.

-K
