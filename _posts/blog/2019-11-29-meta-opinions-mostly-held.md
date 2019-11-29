---
layout: post
title: Meta Opinions, Mostly Held
tags: []
---
If you're in the software industry, you've probably heard the expression "strong opinions, weakly held".  If you're hanging around software discussion sites, you've probably seen the article calling it [the worst idea in tech](https://blog.glowforge.com/strong-opinions-loosely-held-might-be-the-worst-idea-in-tech/).  Michael Natkin points out that if you have "strong opinions", it's very difficult to actually keep them "weakly held".  More importantly, it's nearly impossible to communicate the "weakly held" part.  An engineer with loud, strongly stated opinions can shut down discussion before it starts, and prevent valuable voices from being heard.  

Michael's suggests adding an uncertainty measurement to your statements.  "I'm 90% sure MongoDB is the wrong choice", or "I'm 40% that the bug is in this method".  

Around the same time, Camille Fournier wrote a post about [Other People's Problems](http://www.elidedbranches.com/2019/05/opp-other-peoples-problems.html).  Every company has problems, and everyone has opinions about those problems.  When should you get involved, and when should you stay silent?  How hard should you push when another team's problem affects your team?  Camille outlines five steps to navigate these delicate situations.  

Together these posts have led me to a useful framework for decision-making.  As a senior engineer, I rarely have direct authority to just "fix it" - at least not for the large and interesting problems.  But I also have a responsibility to raise issues and advocate for better solutions.  I need to find a balance:

- How sure am I?
- How much do I care?
- Based on these factors, how far am I willing to push?

## The Scale: 10 Points for Gryffindor

The two factors (certainty and caring) both feed into a 10 point scale.  If I'm advocating for something, I try to put a number on it first - either explicitly for others, or just in my own head.  This helps reign in heated arguments, and leads me to a more effective and stress-free existence. 

### 0-2: The Minor Leagues

Yes, the scale starts at 0 - because we're programmers, but also because a 0-point opinion is a useful thing to have.  It's reserved for explicitly "safe spaces" like brainstorming sessions.  I'm usually a reserved sort of person, but sometimes it's worth throwing out ideas with no filter.  And hey, maybe we *should* rewrite everything in Javascript?

### 3-6: Normal Life

This is where most work happens, but it's still a range.  For example, let's consider a code review.  If I suggest a five-line simplification, that's probably a 3.  I'm pretty sure it will work - but I haven't applied the change and run the tests.  I'm pretty sure it makes the code better, but I'd listen to an opposing argument.  Either way, this is just a discussion between two engineers.  

For a larger example, let's say my team is developing a new feature.  I may write a high-level "vision" for the work - similar to the pitch in Basecamp's "Shape Up" process.  For the first draft, I might have a 4-level conviction that this is the right approach.  As other team members help to improve it, I may go up to a 5 or 6 - strong enough to cheerlead the work into our roadmap.

### 7-10: The Serious Stuff

A 7 or 8 issue is rarely a purely technical or product question.  These are where managers earn their money.  Company values, like a "no assholes" rule, are in the 7-8 range to me.  These aren't "big bright lines", but they are important considerations when making decisions about my career.

A technical issue can rise to the 7/8 range, if it illustrates something about the company culture.  Facebook's infamous "move fast and break things" slogan told everyone about their priorities.  An engineer's agreement (or disagreement) with that slogan may be a 7/8 issue. 

I'm reserving 9 and 10 for ethical issues.  Fortunately I've never encountered a 9+ issue at work, because these are the "resign in protest" sort of decisions.  

## Using the Scale

If Natkin's percentages are estimating odds, my point system is like placing bets with real money.  The "money" is time, effort, political capital - and yes, occasionally real money.  If something's a 3, I'll happily discuss it for a few minutes.  If something's a 6, I'll write up a document and have a series of discussions.  If something's an 8, I'll raise it up the management chain.  

Numbering these bets help me - first within my own head, then when communicating to others.  It's easy to get caught up in a discussion and lose perspective - "no, that design is terrible because..."  Ok, how "terrible"?  Company-threatening terrible?  Are you convinced that this can't work at all, or are you predicting future maintenance problems?  

This process has worked for me personally over the past several months.   Will it work as a more general communication pattern?  I hope so!

Right now I think:
- This is a useful framework for myself (7/10)
- This will be helpful for my coworkers (5/10)
- This will be helpful for strangers on the internet (4/10)

Does it work for you?  [Let me know!](https://twitter.com/tmorton)
