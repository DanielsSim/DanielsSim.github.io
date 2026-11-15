---
title: "If you're (in) a large organization, why are you so inefficient?"
date: 2022-08-06T08:00:00+02:00
categories: economics long_read
draft: false
---

(Crosspost: [Reddit, includes comments + discussion](https://www.reddit.com/r/slatestarcodex/comments/whyd2k/if_youre_in_a_large_organization_why_cant_you_do/). Reading length: maybe 5..10 minutes. Sorry for the messy structure: my thinking is not organized, so my writeup shouldn't be either.)

I've been thinking about this a lot lately. After discussing this with several people I trust, I find the answers I have come up with still lacking and I'd appreciate feedback and pointers to things I'm missing. 

I've been struck recently with how bad large organizations are at getting stuff done. My own workplace experience: It usually costs 30..70k $ to answer some question (estimate from smaller projects I've run: includes getting a few people together, gather technical equipment and do experiments, discuss, produce a 10..20 page report). Work in large-scale projects is even worse: often it takes weeks to do something simple, like: agree on what needs to be done, or get some dataset from one party to several other departments (because it involves reformating the data for some excel sheet and getting that back into a dedicated IT system). But it's not just this one company, it's everywhere. Let me illustrate with a few examples I can think of:

1. Cost disease: Getting something done gets more expensive and we don't really know why ([SSC](https://slatestarcodex.com/2017/02/09/considerations-on-cost-disease/), [Wikipedia](https://en.wikipedia.org/wiki/Baumol's_cost_disease))
2. the German COVID app [did cost something between 20 and 130 M €](https://de.wikipedia.org/wiki/Corona-Warn-App#Kosten), depending on how you count costs. My personal estimate of what the budget should have been here is 1..2 orders of magnitude smaller.
3. Basically every megaproject ever. You already know this, but if you need a source: ["Nine out of ten have costs that are underestimated. Nine out of 10 have benefits that are overestimated, and 9 out of 10 have schedules that are underestimated"](https://www.econtalk.org/bent-flyvbjerg-on-megaprojects/#audio-highlights)
4. The FTX futures fund has [a list of all grants given so far](https://ftxfuturefund.org/our-grants/). They are very smart people and I am sure a lot of thought went into what to fund. This is not intended as criticism of FTX, just that when being told that this is a list of the most effective options out there, I am somewhat underwhelmed. (update from december 2022: This now reads a little bit weird as FTX has recently impleded. As the FTX futures fund team was operating independent of the rest of FTX, I think my point is still valid)

So: Why is it so hard to get stuff done once you move from personal projects to work environments? 

I know this is not a very clear problem description, with my examples all over the place. I'm sorta going from "It's really expensive to do X" to "I'd like to do Y faster, or more of it", with Y being some small subset of X. Or whatever, I realize the problem is not well-thought-through, I'm just really fed up with how difficult it is to actually get stuff done once you move from a one-person project to an organization framework. 

## Possible answers and where to look for info

This is an unsorted list of concepts I've found so far while looking for an answer. I'm looking for more of these, ranging from advice on what to do / to avoid up to fundamental criticism (like: am I posing the wrong questions? Or looking for the wrong kind of answers?). 

### Infrastructure and logists are hard

This includes paying people to run a solid computer network, taxes, logistics within the company, data logists and setting up programs in a way that scales.

(Example: As a private person, when my 300€ laptop running a wild mix of free software stops working I take it to some friend who's good with it debugging. Also I can tolerate a few days without a computer and switch to some other model without compatibility worries. Companies need corporate software licences, the same laptop for everyone, documentation that allows someone else to pick up where on person left, ... and suddenly you're stuck to using hardware that costs a four-figure sum per person and year. The same logic applies to everything else, like moving or getting stuff from a to b.)

What to do about it: Um, I dunno. If you're trying to improve the world, maybe improving the way infrastructure works or providing infrastructure for free to good causes may actually be worthwile or even high-impact.

### Humans are loopy creatures

(concept from the ACX book review contest entry on the extended mind. You can find it included [in this google doc from OT220](https://docs.google.com/document/d/100kMdSVFviZSSBvUyyEQPMNlvLptVQxHFD9i9wGuBWs/edit?usp=sharing). Probably I'm misapplying it here) 

Humans are fast learners and there's a huge difference between doing something for the first time, the second time and beyond. Stuff usually works when organizations are doing things in a loopy way (like a house company building 10+ houses each year). A guide to screwup is when people are doing something for the first time, but in a tight scedule on a shoestring budget (basically every megaproject ever).

What to do about it: Place people (including yourself) in positions where they get to redo stuff in a reasonable frequency. Stay away from all projects doing something for the first time without a sufficient safety net.

[Also see the recent discussion here on the reddit on HVAC installation costs.](https://www.reddit.com/r/slatestarcodex/comments/vyb6iy/british_hvac_installers_seem_weirdly_bad/ig1unbl/ ). Apperently there are some scaling laws I wasn't aware of, [this comment](https://www.reddit.com/r/slatestarcodex/comments/vyb6iy/british_hvac_installers_seem_weirdly_bad/ig1unbl/ ) refers to [Wikipedia on experience curve effects ](https://en.wikipedia.org/wiki/Experience_curve_effects) and [Swanson's law](https://en.m.wikipedia.org/wiki/Swanson%27s_law). 

### Look for good opportunities

There's the standard project planning triangle with costs, time and quality on the three sides, and you can only get two out of three. Well, what if we remove time from the target list? 

Sometimes the stars align and just the right circumstances occur to solve a problem at a fraction of the usual costs: Someone has the right hardware needed around, maybe you can piggyback on an existing investigation, or you happen to meet someone who already knows the right puzzle pieces. I've seen this occur over and over and now that I'm compiling the list, it came back to my mind. Problem with this: doesn't work if you're on a tight schedule.

What to do about it: Having a list of unsolved / open things helps. If the right situation occurs, you want to notice. Even better, you want someone else to tell you, so telling other people what your open / unsolved issues may be the thing to do.

(Probably there's also some effect of [cognitive load](https://en.m.wikipedia.org/wiki/Cognitive_load), where "how much mental capacity you have available to focus on some open issue" very much affects the possible solutions. For years I made fun of [mental load](https://www.theguardian.com/world/2017/may/26/gender-wars-household-chores-comic), but these days my brain is so full that even simple stuff like "pick a gift for a friend on Amazon" is a tricky thing to fit into my schedule)

### Worry about the critical path

Some fine person from my local lesswrong meetup pointed me to what Tesla is doing (shoutout to the Karlsruhe rationality group). Apparently there's some guy, Joe Justice, running around giving talks on how amazing it is. I found [this conversation here](https://www.youtube.com/watch?v=AKqKCn4fheY&t=0) quite helpful: among many other things, they appear to devote significant energy to finding and clearing the critical path in their timings: There's always something that lots of other parts of a huge task depend on and you REALLY want to notice what it is and then get it done.

What to do about it: Have mechanisms to identify the current bottleneck. Have a way to shift capacity of competent people to working on it.

### Maybe my reference frame is wrong

Writing this post took me maybe 5 hours of my private time. But this happened over several weeks in small bursts (whenever something pops on my mind, someone gives me a good hint and I have a few minutes to spare) and I started because I already had a personal interest in the topic and because I felt I have sufficient access to the right people to get good answers. Doing the same thing on a set schedule ("work") would probably have increased the time needed by A LOT just of the way opportunity works. Also, I value my private time at maybe 10 bucks/h which is an order of magnitude below costs in a work setting. 

What to do about it: Just update my priors and expect stuff at work to take very long and be very expensive. 

## Consequences

The answers I've found so far fall into two categories:

For one thing, I previously failed to take into account how rigid, slow and cost-intensive any organization is. Organizations excel in repeated tasks, where optimization opportunities arise and experience curves apply. Lots of my initial examples are exactly the opposite, involving stuff that's new and that requires relatively fast and coordinated action. The resulting "organizations are not fast for anything new"-model generalizes well to reality. To give a few examples:

 - the model implies that large companies may be better off buying small startups for innovation than funding their own internal innovative research.
 - politicians taking over a ministry often rely on external consultant companies (McKinsey etc) to get stuff done. This has been heavily criticized at least in German media, but I realize that this makes a lot of sense if "do it internally in your ministry" is not an option because of the fast+new aspect of the task at hand
 - under that model, having a "fixer" role is very useful for any large org as screwups inevitably occur and the structure is not good at handling them by default. You know, like the Wolfe guy in pulp fiction. 

This does not imply that organizations are totally immune to change, they are just very slow with it. Also this does not mean organizations are bad: there are lots of things organizations do really well, like structured processing of complex tasks. For example, logistics are really hard (see above) and logistics companies navigate getting stuff from a to b really well! We just shouldn't expect, say, the Amazon logistics department to be good at solving any non-logistics problem it encounters for the first time.

The second set of answers is practical advice on how to defy that model from above (worry about the critical path, look for good opportunities,. ..). Part of this feels like general project management, but I feel I should know more of these. Any additions are highly appreciated.