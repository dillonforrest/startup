---
layout: post
share: true
comments: true
can-subscribe: true
title: "Open source as a startup's competitive advantage"
tags: best
---

I previously mentioned that open source can be a solo founder's <a href="http://www.dillonforrest.com/startup/the-competitive-advantages-of-a-solo-founder/" target="_blank">advantage</a>. Today I want to further delve into open source for business value.

# Positive takes on open source

Tom Preston-Werner wrote that GitHub chooses to <a href="http://tom.preston-werner.com/2011/11/22/open-source-everything.html" target="_blank">open source (almost) everything</a>. He argues that open source creates business value in several ways:

- It's great advertising for your company
- It enables more work done faster when external developers contribute
- It attracts, screens, and retains developers
- It produces more robust software

Open source works incredibly for GitHub. I'm interested in replicating certain parts of their model hoping to derive some of the same business value and some of the same fun, because let's face it, developers think open source is pretty damn sexy.

# Negative takes on open source

Unfortunately, not everything is awesome with open source. Sacha Greif wrote that open source can be <a href="https://medium.com/@sachagreif/open-source-lessons-learned-two-years-of-telescope-be4ed955b39" target="_blank">a lot harder</a> than you'd think. Sacha maintains <a href="http://www.telescopeapp.org/" target="_blank">Telescope</a> and generally has a much less rosy view on open source. He shared some sombering experiences:

- He expected to receive lots of work from other developers, but he did most of the coding still
- Telescope created additional work for him, such as writing documentation and providing support, while receiving zero revenue
- Successful open source projects have users who are also developers who want to contribute, and Telescope didn't have many users who were developers

The biggest takeaway for me from Sacha was that open source is about building your community. With no community, there's no business value from open source.

# Reconciling both sides

So, how do we make sense of both of these points of view? I believe I can reconciliate both sides.

#### Utilities vs. applications

Open source utilities can derive much more business value than open source applications.

It's a semantic discussion, but for this post I define the difference between the two as the portal through which consumers interact with the software. Utilities are consumed via an API. Applications are consumed via a UI. Rails, react, git, linux, underscore, clojure, node are all software intended to be used programmatically via APIs. Facebook, Twitter, Gmail are all applications which use their UIs to allow users to create, retrieve, update, and delete records.

Software meant to be consumed through an API will naturally have only developers as its userbase. Only developers care about software accessible via an API. Applications' userbases will have small amounts of developers. I believe utilities are stronger candidates for open sourcing than applications if you want to derive business value.

#### Popularity

Most of Tom's open source benefits are predicated by popularity. You'll only receive patches from external developers if your project is popular.

Sacha's Telescope project is by no means unpopular. As of this writing, it has over 2,900 stars and 93 contributors. Seriously awesome open source accomplishment by Sacha. None of it would have happened without Sacha's hard work to develop his communities. Sacha worked damn hard to cultivate his community, and I think he's seeing the results.

#### By developers for developers

Tom's post suggests the benefits of open source are trivial to realize. The reality is probably closer to the opposite. It's probably difficult for most people to find value in open sourcing their code.

GitHub is a company built by developers for developers. The cofounders were all extremely technical. They aren't your typical bottom-bucket startup founders who think they're Max Levchin but can't use version control or write unit tests. Their target customers are developers and engineering teams. They're a company by developers for developers.

If your company is built by developers for developers like GitHub, you should strongly consider open source.

# Commoditizing complements

Another open source thought which neither Sacha nor Tom mentioned is one of the most popular open source business models.

Economically, when a good or service becomes commoditized, demand for its complementary goods and services increases. When more people adopt your free open source software, they will demand complementary goods and services. You can provide these complementary goods and services.

# My open source plan

Am I currently trying to solve problems for developers? <a href="http://www.dillonforrest.com/startup/month-4-february-2015-wrapup/" target="_blank">No</a>. Therefore, I won't open source anything, not yet at least. I can't justify the costs of open sourcing just yet.

Tom says that to get great advertising out of open source, you need to "do it right." Open source can be done correctly or poorly. He shares one tactic where GitHub announces closed software soon to be open sourced. GitHub gauges the public's reaction and then launches accordingly.

When (not if) I get a few customers, I'll start making announcements to open source some of my code. I'll decide my next step after seeing the reaction.

Is this what Tom means by "doing it right"? I'm not sure. I haven't really done much right yet.
