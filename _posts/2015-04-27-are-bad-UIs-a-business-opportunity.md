---
layout: post
share: true
comments: true
can-subscribe: true
title: "Are bad UIs a business opportunity?"
---

My most recent way to find underserved market gaps was finding existing businesses which had paying customers who were frustrated with their user interfaces. I'd like to share my thoughts with you on how to find a business opportunity when you spot frustrating UIs.

# The GUI

The most common UI is the graphical user interface, or the GUI. Almost 100% of tech companies have a GUI. A GUI can be either a web app, desktop app, or mobile app. They present form fields, widgets, buttons, and text. Oftentimes the GUI's main job is to allow you to create, retrieve, update, and delete records in a database.

Despite the GUI's dominant market share, not everybody has a GUI that customers love. In fact, I'd argue that most GUIs offer poor user experiences. Many of these GUIs are frustrating due to either poor technical implementation or poor design sense. Some companies just can't afford or retain quality engineers and designers. However, in my opinion, some companies simply will never make their users happy with their GUI because a GUI is the incorrect solution for their customers and their domain.

My hypothesis is that you can serve a frustrated customer segment by choosing a better interface for them. An API is a popular alternative, but there are other options to consider to capture business value.

# Alternative: The CLI

"CLI" stands for command line interface. A CLI is the terminal application on your computer, or any read-evaluate-print loop (REPL).

Pros of the CLI:

- All unix philosophy benefits, particularly composability, which implies network effects since CLIs' utility is an expential or even factorial function of the number of CLI tools available. You can pipe, grep, tail, curl any of your CLI outputs with any other CLI or vice versa.
- A text-only REPL interface coerces simplicity. There's no huge canvas to fill with useless UI widgets. The naked text forces everybody to consider only utility.

Cons of the CLI:

- It's ugly. Only programmers will be comfortable using a CLI. There are immense branding problems and switching costs associated with ugliness.
- It's not good without a keyboard. CLIs are amazingly rich and expressive due to their emphasis on text rather than pointing and clicking with your mouse. However, no utility without a keyboard means no utility with mobile and tablets.
- It requires its users to be at least moderately technical. People have know how to use their terminals to realize any network effects benefits. People need to be comfortable with man pages and documentation. There's a larger switching cost than ugliness even.

# Alternative: an email-first interface

The best example I can think of for an email-first product might be <a href="https://idonethis.com/" target="_blank">iDoneThis</a>. iDoneThis has a useful GUI as well, but I think email is its primary interface.

Pros of email:

- You can pop up in your user's inbox rather than make them go out of their way to log into your GUI. This is good for engagement.
- You can still use all static markup to make your emails pretty.
- Email is much cheaper to iterate than a GUI. A GUI is an entire codebase. An email is just text.

Cons of email:

- It's a slow feedback loop. Email is appropriate for occasionally creating, updating, or deleting records in your database. It's not appropriate for frequente creates, updates, and deletes.
- It's not elegant for your customer to make on-demand requests to retrieve records from your database.

iDoneThis combines their email interface with their GUI to get the best of both worlds. Most companies don't do this, even though they have rarely used or frustrating GUIs.

# Using this to find business opportunities

The GUI will always be the market leader. However, if you want to find a market niche, starting without a traditional GUI might be a great opportunity, particularly if your users might prefer a different interface.