---
layout: post
share: true
comments: true
can-subscribe: true
title: "The benefits of clojure for starting up"
---

I previously wrote a post called <a href="http://www.dillonforrest.com/startup/why-im-using-clojure-to-start-up/" target="_blank">"Why I'm using clojure to start up</a>. My post ended up being more about why I'm using a bleeding edge tool rather than an older predictable albeit boring tool. This post is meant to correct that error and explain why I'm using clojure rather than other bleeding edge tools.

# Interop with java and javascript

Clojure and clojurescript are modern dialects of lisp which compile to java bytecode and javascript respectively. That means that clojure and clojurescript have ecosystems at least the size of those of java and javascript. Java and javascript are immense communities with immense open source options. I chose the word "immense" purposely. Nothing else can describe the vastness of either java or javascript alone, let alone together.

Countless smart programmers invested countless hours into building java and javascript tools. Clojure and clojurescript allow direct access to these tried and true tools. I mentioned that my engineering choices were meant to minimize cost, not risk, but the reality is that clojure and clojurescript are choices which minimize risk as well. I should never have to repeat any work already done in either java or javascript.

# Stronger abstractions

To define "stronger abstractions" in a business sense, it means spending more time on problems directly related to creating business value and less time on problems having no direct tie to business value but inhibit business value anyway. Engineering is an interesting group in a software company because your engineers drive not just your top line but your bottom line as well. Engineering can become immensely expensive when you use weaker abstractions. Your engineers will spend more time solving the problems which don't matter so that eventually they can solve problems which do matter.

The specific design decisions and abstractions in clojure which I expect to minimize costs are the following:

- **Immutability**. Engineering is a super giant rubics cube. To solve it, you need to know each moving part. When you get all the moving parts to finally be in the correct locations and move together, that's when you've solved it. Immutable data structures don't move. The less moving parts you have, the more brainpower you save to focus on better things. With immutability, clojure and clojurescript allow the programmer the luxury to worry about more important tasks. Immutability means no costs associated with mutable data structures.

- **Communicating sequential processes**. Asynchrony is a complexity multiplier, and in software complexity means cost. Synchronous software is much simpler and easier to reason about, and thus less expensive. Unfortunately, despite its costs, asynchrony is inevitable. Communicating sequential processes (CSP) is a model for writing asynchronous software (expensive) in a synchronous fashion (cheap). For more information, I'd recommend David Nolen's <a href="http://swannodette.github.io/2013/07/12/communicating-sequential-processes/" target="_blank">post</a> about CSP in clojurescript.

- **Homoiconicity**, or "code as data." This is a more technical point, and I think Adam Bard <a href="http://adambard.com/blog/what-is-homoiconicity/" target="_blank">explains</a> its importance better than I could. In sum, you can write code which writes more code. This is called a macro. Paul Graham doesn't exactly connect all the dots for the reader, but he touches upon the business value behind macros in his essay about <a href="http://paulgraham.com/avg.html" target="_blank">beating the averages</a>.

# Faster feedback

Lean startup methodologies are valuable because they encourage shortening the feedback loop. Faster feedback means faster progress. The same is true with code. Faster feedback on your code means more correct code written in a shorter amount of time.

Most productive languages have a tool called a repl which permits high interaction and faster feedback. Dave Jarvis explains the value of the clojure repl <a href="http://blog.venanti.us/why-clojure/" target="_blank">here</a>.

# Is clojure appropriate for starting up if you're new to clojure?

I don't have any production experience with clojure or clojurescript. So far, I would say that my beginner status hasn't been a meaningful hindrance. Although I needed some help to figure out how to set up my development environment, most everything else was more straightforward for me to figure out myself. My main weapon of choice before clojure was javascript. I'm definitely much more productive in clojure than I was with javascript.

As a one-person team, I'm always looking for ways my efforts can compound over time. Investing in stronger tools is one of them.