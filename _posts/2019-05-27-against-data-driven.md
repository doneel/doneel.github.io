---
layout: post
title: Against Data-Driven
categories: work
---

# {{ page.title }}

My job in data engineering is predicated on the value of data, but I don't believe in being "data-driven" at startups. This is a personal manifesto after talking to a few too many startups which have assured me they're data-driven.

At its steelmanned best, data driven means allowing the objective evidence to outweigh opinions and subjective judgement at the strategic and tactical levels. Being data driven means applying as scientific of a method as possible. Of course there's always some judgement in framing what decision to make in the first place, but data driven pushes us to ground our theories in reality and reminds us to *weakly* hold those strong beliefs.

I don't believe those benefits are worth it for startups both because it blinds you from thinking bigger than than your ability to measure and because it incentives you to optimizing the wrong things.

## What's wrong with data driven culture?
First, I don't believe it'll lead to make better decisions in an absolute sense or relative to your competitors.

1. Is your ability to learn through data actually an advantage? If your thesis is that you're building something fundamentally new, probably not. If you're outcompeting an incumbent, you probably don't have a data collection advantage.
2. Most things you *should* build as a young tech company don't exist. It's hard to collect data on things that don't yet exist. Biasing your focus towards measureables leads you to local optima, which shouldn't be your product's goal until you're well beyond product market fit.

Second, the 2nd order culture effects squash agency from the bottom up.

1. Trying to be data driven incentives management to optimize for legibility of their products and teams. Once you impose metrics, the technical and organization's mechanisms for collecting and using that metric become sticky defaults. When metrics are perceived to be the justification for products, they're untouchable without slow, top down approval. *You can't just change the product if that would mess with the metrics*. Designing processes and products to be measureable has a compounding long term cost.
2. Data driven decisions remove the perception of decision responsibility off of individuals and into a process. Maybe(?) that's great when you want to suppress egos and charisma from drowning out quieter voices. But it's definitely bad when you want ideas to bubble up and when you want a culture of ownership.

## No substitute for judgement

Instead, at the early stage we should be embracing judgement. Individuals should own decisions and use their full range of direct experience, pattern matching, intuition and analytical skills to make the best decision they can.

More *wrong* decisions will be made than in data driven culture, and for that reason we need a culture both less *tolerant* of bad decisions but more *forgiving*. 

More disagreement will arise than in data driven culture, but unlike in data driven culture, it's not always a bad thing. Disagreement should flow freely when people feel that their own personal judgement matters. 

A culture that relies on personal judgement is more defenseless against egocentric or inflexible thinkers but in return, it allows individuals to bring their full depth of experience and thought.


### The role of data in judgement culture
Use data as a preferred mechanism to test your hypothesis rather than extracting a hypothesis from data you already have.

- **Experimentation informed by data**. A/B testing, smoke testing and other controlled experiments are a way to get the "data driven" benefit of objective decision making while learning about predefined hypotheses. Just don't limit yourself to only changes you can test! Data shouldn't be the *driver*, but it can be that annoying pre-iPhone GPS with perennially outdated maps and no idea about traffic: helpful for navigating most individual turns, but not good at picking routes or destinations.
- **Build metrics, but don't build them into your official process**. The moment it becomes common knowledge that we'll regularly review a metric is the moment that leading indicators become games and lagging indicators become distractions. It might be imperceptibly slow, but I'm convinced it's inevitable.
- **Be skeptical**. As a rule, those who build metrics from raw data are more confident in the raw data than those who actually collected it. As a rule, those who view metrics are more confident in those metrics than those metrics than those who built them. Treat any metrics that involve customers the way you would treat hearsay from a gossipy relative: always over-narrated, usually 2nd hand, often driven by a personal agenda, and occasionally insightful.

### Caveats

1. When I hear the term used by companies, I think it's earnestly meant as a sign that they're humble enough to change course and that they're true believers in the mission even if it doesn't fit their personal vision. That's good branding and good leadership so maybe I'd self-identify with term too in some context.
2. This is all about product culture, not monitoring of technical systems. System metrics like uptime or response time SLIs are not about about peering into an overdetermined fog of war, they're about visibility into a closed system. Instrumenting systems and monitoring and reviewing metrics is good.
