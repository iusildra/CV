#

## Hello 👋

### Who am I ? 🔍

A french master student in computer science at [Polytech Montpellier](https://www.polytech.umontpellier.fr/english/), enjoying learning new things and aspiring OSS contributor.

Fan boy of functional programming and the [Scala](https://www.scala-lang.org/) language.****

### What am I doing ? 📚

I am currently working on the Scala tooling (debugger) for my 4th year internship at the [Scala Center](https://scala.epfl.ch/) 👉 [scala-debug-adapter](https://github.com/scalacenter/scala-debug-adapter)

At the same time, I started to contribute to the [Dotty](https://dotty.epfl.ch/) project (the Scala 3 compiler)

I also joined 2 conferences as part of the core team:

* [Sunny Tech](https://sunny-tech.io/) a french conference happening in Montpellier at the end of June, about anything related to tech: programming, security, devops, UX, etc.
* [ScalaIO](https://scala.io/) a french conference happening in Paris at the end of October, about Scala and functional programming, mainly, but not only (Haskell, Clojure, etc.)

### What am I looking for ? 🎯

To upgrade my knowledge about Scala to develop a strong expertise in this language and more generally in functional programming design.

### What are my professional projects ? 💼

I don't really know yet, something on Scala for sure

Teaching at some point would interest me too


## Scala Debugger Improvement

I improved the Scala debugger in VS Code by creating a new evaluation mode that is faster and more flexible, with reflection. This new mode allows access to private members and runtime types, including fields and methods that are unreachable with compile-time type.

I encountered some challenging problems, similar to those of a compiler:
- Type checking
- Types resolution
- Overloads resolution

The evaluation was about 6 to 9 times faster than the current evaluation mode. However, this speed is influenced by the source code's size and number of loaded classes. Also, it cannot evaluate every expression (generics, for instance). It is complementary to the current evaluation speed.

I intend to keep upgrading it to make it more efficient, accept more expressions, and correct bugs.

I also made my first steps in the Dotty compiler with the "compiler academy".

