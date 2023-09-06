# ScalaBridge @ Scala Days Madrid 2023

This is a quick guide to the [ScalaBridge event][scalabridge] happening at [Scala Days Madrid 2023][scala-days].


## Time, Date, and Location

* Date: September 12th
* Time: 8:30 am to 3:30 pm
* Address: [Sede Madrid-Argüelles, Room 503][address], Calle de Quintana 21, 28008, Madrid, Spain. 


## How It Will Work

There are two groups of people: students and mentors. We have specific sections for each of you below. On the day we will form groups of students who want to work on similar things, and assign a few mentors per group. Then we get to work! Before we finish at 3:30pm will have a little bit of time to show what we've accomplished.


### Students

We have prepared two projects that you can work through during the day:

* [Stoop][stoop] involves implementing a series of little programming languages, that culminates in a small but Turing-complete language with a Scala-like syntax. (A stoop is small set of stairs for entering a house.) This project is appropriate for people with some existing Scala knowledge.

* [Composition and Cycles][spirograph] involves implementing code to draw images like those produced by a physical [spirograph][wiki-spirograph]. This project is appropriate for people very little Scala or programming knowledge. This project is part of a book, Creative Scala, that teaches programming assuming no prior knowledge, so we can start as early as needed in the book to get you the knowledge you need.

This event is about you, so we're not trying to force you into a particular pathway. If you choose one of the projects above, don't feel that you have to complete it all. Take time to explore things that you find interesting. This session is about learning, not about meeting a deadline. You can do something else if you want. There is a good chance there will be a mentor who is able to support you, whatever you choose, but be aware you can't expect the mentors to improvise a lesson on the spot. If you go this route expect to do a bit more work yourself, with the mentors acting more as collaborators than guides.


### Mentors

It's a good idea to take a quick look at the above projects before the day. A few things to note:

* For the [Composition and Cycles][spirograph] project, students can start as early in Creative Scala as they need to. This can be right at the beginning if they have no programming experience. The following chapters cover the essential concepts:

  - Expressive Expressions covers the basics of using Doodle to create graphics.
  - Structural recursion over the natural numbers is the core programming technique.
  - Points, Paths and Polygons discusses how to represent points using polar coordinates, and how to create paths
  - Functions and Flowers covers functions and parametric curves.

* For the [Stoop][stoop] project, [PLAI][plai] will guide the students through the implementation. However PLAI uses the [Racket][racket] programming language, which may be confusing to students. There is a fairly direct conversion to Scala. It's all algebraic data types and structural recursion. There is a thorough explanation of these techniques in the Scala context in the [WIP version of Scala with Cats][scala-with-cats].

[scalabridge]: https://scaladays.org/madrid-2023/scala-bridge
[scala-days]: https://scaladays.org/madrid-2023/
[address]: https://www.urjc.es/universidad/campus/sedes#situacion-y-planos-2
[stoop]: https://github.com/creativescala/stoop
[spirograph]: https://www.creativescala.org/creative-scala/cycles/index.html
[wiki-spirograph]: https://en.wikipedia.org/wiki/Spirograph
[plai]: https://www.plai.org/
[racket]: https://www.racket-lang.org/
[scala-with-cats]: https://scalawithcats.github.io/scala-with-cats/