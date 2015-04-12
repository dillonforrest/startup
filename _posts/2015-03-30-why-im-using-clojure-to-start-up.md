---
layout: post
share: true
comments: true
can-subscribe: true
title: "Why I'm using clojure to start up"
tags: best
---

I came across this <a href="http://mcfunley.com/choose-boring-technology" target="_blank">awesome post</a> by Dan McKinley. Dan argues that when building software, you should resist the urge to use sexy bleeding-edge tools and instead prefer building with reliable albeit boring technology. Prefer php and mysql over clojure and datomic. The reason is that there are far more unknown unknowns with bleeding edge than there are with boring but reliable. To me, the gist of Dan's post is this:

> It is basically always the case that the long-term costs of keeping a system working reliably vastly exceed any inconveniences you encounter while building it. Mature and productive developers understand this.

I agree with Dan. I'd say that the unknown unknowns with boring but reliable tools is close to zero. For many types of businesses, this is the safest way to stay in business and continue growing. However, for my own startup attempt, I'm decisively sticking with clojure, clojurescript, and datomic. Dan is a smart engineer, way better than I am probably, but I'm discarding his advice. Here's why.

# Minimizing cost vs. minimizing risk

Dan previously worked at Etsy, and now he works at Stripe. These two companies have real business models with real customers, revenues, employees, and reputations on the line if they make huge mistakes. Naturally they should be risk averse. A technology gamble's potential upside isn't worth its potential downside for these companies.

If you're a nascent startup struggling to get off the ground like myself, you have nothing to lose and everything to gain. You're not risk averse. You want risk. Risk means a chance to become relevant.

At the same time, I don't have the budget to deal with the short-term costs of boring but proven technology. I have only my savings as my lifeline. I need to minimize my costs.

I chose bleeding edge because my risk profile and my budget don't suit boring but reliable technology.

# Mature and productive developers

Stripe and Etsy's engineering teams both have extremely strong reputations in the industry. I imagine they have a much less difficult time attracting engineering talent than almost anybody else. I don't doubt that they have plenty of mature and productive developers. These guys can kick ass with whatever technology they choose, bleeding edge or boring but reliable.

Most engineering teams are not like Stripe's or Etsy's. Mature and productive engineers tend to clump together and all work at the same few places, leaving less engineering acumen to go around for the rest of the market. These teams still choose boring but reliable technology, but without the same success. The short-term costs drive the teams to break their technology with every single production deployment. I've seen this with my own eyes. Most engineers are not mature and productive. Most engineers will in fact succumb to the short-term costs of boring but reliable technology. And then, these engineers won't reap the long-term rewards either. It's the worst of both worlds.

I don't have a team of mature and productive developers. I have only me and my 3 year old Macbook Air. I'm a solo developer who has bad dreams about how good at programming I simply am not. The short-term costs of boring but reliable are enough to sink a team of one. Bleeding edge is a productivity cheat code that I won't pass on.

# Best tool for the job

Dan's post is super awesome (go read it immediately after finishing my own!), so I'm sharing another valuable excerpt:

> The problem with "best tool for the job" thinking is that it takes a myopic view of the words "best" and "job." Your job is keeping the company in business, god damn it. And the "best" tool is the one that occupies the "least worst" position for as many of your problems as possible.

My job isn't to keep my company in business. It's to create business for my company. Although I totally respect Etsy and Stripe's decisions for php and ruby respectfully, and although I totally look up to both of those companies for having amazing engineering, I'm just not at the same level and can't make the same decisions. I'm just me. My least worst option is undoubtedly bleeding edge.

(Edit: A few readers pointed out that this post discusses my choice for bleeding edge technology rather than clojure specifically. I corrected this mistake by enumerating clojure's benefits to create business value <a href="http://www.dillonforrest.com/startup/the-benefits-of-clojure-for-starting-up/">here</a>.)