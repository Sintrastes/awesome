# Nate's Awesome List ![Awesome](https://awesome.re/badge.svg)

My own personal [awesome list](https://github.com/sindresorhus/awesome/blob/main/awesome.md) in a variety of topics.

# Software Engineering / Architecture

  * [A Few Thoughts About Path Coverage](https://blog.regehr.org/archives/386)
    * Some interesting thoughts on what it means for a code-base to really be thoroughly unit-tested.
    
  * [Unit testing isn't enough. You need static typing too](http://evanfarrer.blogspot.com/2012/06/unit-testing-isnt-enough-you-need.html)
    * An interesting case study showing the benefits of static typing. Also interesting to me is the fact of how the Python projects studied could essentially be translated more-or-less directly into Haskell -- there were not any dynamic typing idioms that the Haskell type system was "too restrictive" to handle.
    
  * [3 tribes of programming](https://josephg.com/blog/3-tribes/)
    * Incredibly elucidating analysis of the cultural divides within the software engineering community. Also, explains why I really like Rust. :)
    
  * [Sum Types are Not a Silver Bullet](https://sintrastes.github.io/blog/posts/2021-07-19-sum_types_are_not_a_silver_bullet.html)
    * This is something I wrote -- but I think it's an incredibly important lesson when trying to architect applications and systems in a functional style.

  * [Abstraction: Not What You Think It Is](https://www.pathsensitive.com/2022/03/abstraction-not-what-you-think-it-is.html)
    * People in the software engineering community (especially in the context of object-oriented programming) often talk about code as being "too abstract" -- but is that really the issue? This post gives a fascinating analysis of the different things that people mean when they talk about "abstraction" in software engineering, and forces you to define your terms (and maybe ask others to define their ters) for clearer discussions. 
    
  * [No-code, no thought Substrates for simple programming for all](http://tomasp.net/blog/2022/no-code-substrates/)
    * An interesting take on the "no/low code revolution" that will inspire you to think of ways to make your application more flexible and your capabilities for customization more discoverable -- or at least that's what I got out of it.
    
  * [The future of software, the end of apps, and why UX designers should care about type theory](https://pchiusano.github.io/2013-05-22/future-of-software.html)
    * Applications of type theory? Democratization of software development? Making it easier to glue together functionality without a lot of boilerplate, rather than sandboxing everything into black-box "apps"? Yeah -- safe to say this hits a lot of "awesome" points in my book. Also, I feel like this is very similar in theme to the above post by Petricek.
    
 * [Knowledge as Code](https://carboncloud.com/2020/12/07/tech-knowledge-as-code/)
     * An interesting perspective on the advantages statically typed functional programming could have on your organization.
     
 * [Execution in the Kingdom of Nouns](http://steve-yegge.blogspot.com/2006/03/execution-in-kingdom-of-nouns.html?m=1)
     * Making fun of enterprise OO may be like [shooting IMarineVertabrates in an AbstractBarrelProxyFactory](https://fsharpforfunandprofit.com/fppatterns/), but I still think this makes a fair point for Java developers to consider in the advantages of more modern multiparadigm languages that don't force everything into a <s>box</s> class.

 * [Developer tools can be magic. Instead, they collect dust](https://www.pathsensitive.com/2021/03/developer-tools-can-be-magic-instead.html)
   * Why settle for lackluster developer tooling? This post has some excellent examples of innovative developer tooling that (unfortounately) are currently rather bitrotten, and has some discussion of why this is currently the case.  
   
 * [The Lost Elegance Of Computation](https://www.typetheoryforall.com/2022/05/09/17-The-Lost-Elegance-of-Computation-(Conal-Elliott).html#1fe23b61)
   * Interview with Conal Elliott, one of the progenitors of Functional Reactive Programming. Includes an explanation of his radical approach to software design based off of denotational semantics, thoughts on the current state of PL research, and his general philosophy of Computer Science.

 * [Boundaries](https://www.destroyallsoftware.com/talks/boundaries)
   * Excellent talk on how to design your system to be testable. 
   
 * [Functional architecture: a definition](https://blog.ploeh.dk/2018/11/19/functional-architecture-a-definition/)
   * What is meant by functional design/architecture? Mark Seemann gives a simple, falsifiable definition.
   
 * [A Modern Architecture for FP](https://degoes.net/articles/modern-fp)
   * Another approach to functional architecture.

 * [Parse, don’t validate](https://lexi-lambda.github.io/blog/2019/11/05/parse-don-t-validate/)
   * An introduction to an idea I consider a core tenant of good functional design/architecture -- which is applicable across many different languages.
   
 * [Functional Design and Architecture](https://www.manning.com/books/functional-design-and-architecture)  
   
# Functional Programming

  * [Another Look Through Optics](https://medium.com/@wigahluk/another-look-through-optics-ffd253336e9c)
    * Really interesting perspective (and potential application) of profunctor optics by looking at them through the lens of the profunctors themselves.
   
  * [Monadic profunctors for bidirectional programming](https://blog.poisson.chat/posts/2017-01-01-monadic-profunctors.html)
    * Another really interesting application of profunctors that I don't think has been fully explored.
   
# UI/UX Design

  * [7 GUIs](https://eugenkiss.github.io/7guis/)
    * Finally! An at least somewhat systematic approach to evaluating the various GUI toolkits out there. You can finally put your React/Angular debates to rest (haha, like that will ever happen).
      
      But in all seriousness, this is a fantastic approach -- and I honestly think that more projects in this strain to evaluate even more aspects of the different UI/UX frameworks, with potentially different criteria depending on your particular interest would be very helpful.
      
  * [Slint (formerly SixtyFPS)](https://slint-ui.com/)
    * Like QML's older and better put together older brother. This is just a pleasure to work with. Embedded support too!     
      
  * [Monomer](https://hackage.haskell.org/package/monomer)
    * Nice Elm-like way to build simple GUIs for Haskell.
      
  * [Indigo](https://indigoengine.io/)
    * An Elm-like engine in Scala for pixel art games. A lot of interesting work has been done here on optimization. Functional indie game devs rejoice!

  * [Reflex FRP](https://reflex-frp.org/)
    * I don't know if this is my favorite GUI framework, and it's definitely not the easiest to use (whether or not it _could be_ with more polish, I'm not sure) -- but just for the experience of learning it (like many people say about learning Haskell itself), I'd reccomend playing around with this. It will change the way you think about reactive programming and GUI development. I can say in my experience it has taught me how to use more mainstream frameworks like Kotlin flow more effectively.
    
 * [Purescript Refract](https://github.com/pkamenarsky/purescript-refract)
   * An interesting variation on TEA (The Elm Architecture) making good use of lenses to compose components. Indigo does something similar.

 * [Eve](https://witheve.com/)
   * A fascinating project testing the depths of how user-friendly we can make UI/App development. Fantastic DX/Debugging concepts and experience. Unfortountely the project was canned, but I can only hope future projects learn some of these same lessons. 
 
 * [Fudgets](https://www.altocumulus.org/Fudgets/)
   * Very early (perhaps _the_ earliest?) approach to a truly functional approach to UI design, dating from the early 1990's.

# CS Papers

  * [The Optics of Language Integrated Query](https://arxiv.org/abs/2009.00997)
    * Fascinating and really expressive API for a query language, based on optics. Almost reminds me of GraphQL -- I wonder if there's a relationship worth persuing there.
    
  * [A comparative study of language support for generic programming](http://aszt.inf.elte.hu/~gsd/s/generic.pdf)
    * This (and a lot of [later papers](https://dl.acm.org/doi/10.1017/S0956796806006198) built around the same idea) examines different language's capabilities in the relm of generic programming. I find this very helpful when thinking about things like "What don't I like about language X" or "What feature do I wish language X had" in that specific terms are introduced (such as "Retroactive modeling") that can be used to discuss these ideas with greater clarity. 
    
  * [JavaGI](https://dl.acm.org/doi/10.1145/1985342.1985343)
    * Looks at how to incorporate ideas from functional programming (typeclasses) into Java's existing mechanism of interfaces.

  * [Quickstrom: Property-based Acceptance Testing with LTL Specifications](https://arxiv.org/pdf/2203.11532.pdf)
    * Looks at practical property-based testing of temporal properties based off of a 4-valued graded modal logic.

  * [Feature-Oriented Programming with Object Algebras](https://www.cs.utexas.edu/~wcook/Drafts/2012/FOPwOA.pdf)
    * A fascinating application of object algebras. 

# Programming Languages
    
## Research (Or just cool) Languages

  * [Koka](https://koka-lang.github.io/koka/doc/index.html)
    * Really innovative optimization (reuse analysis) that in many cases can convert functional style code to runtime-less C that mutates in place.

  * [MarkovJunior](https://github.com/mxgmn/MarkovJunior)
    * A language that somehow combines the work of Andrey Markov Jr. (think the Russian School of constructive mathematics), and (by way of a probabalistic interpretation of Markov Algorithms) Andrey Markov Sr. (Think Markov Networks, Hidden Markov Models). This is unbelievably <s>nerdy</s> cool. Also, look at those example gifs! If I don't use this some day (or something similar) for procedural generation of game worlds, I'll be dissapointed in myself.

  * [Refal](https://en.wikipedia.org/wiki/Refal)
    * A language nearly as old as Fortran and Lisp, built on a completely different paradigm (Markov Algorithms) than anything I've ever seen. Why does no one talk about this? 
    
  * [Ante](https://antelang.org/)
    * Very promising looking language which tries to bridge the gap bewtween low-level languages (like Rust) and high-level languages (like Haskell, OCaml). Has a very interesting memory management model -- looks to me kind of "like Rust, but less hand-to-hand combat with the borrow checker". Also has refinement types with type inference.
    
  * [Flix](https://flix.dev/)
    * A proper Hindley-Milner ML for the JVM with logic programming capabilities and an effect system. Potentially of interest to Android devs as it can target earlier Java bytecode -- but I'm not sure what the FFI story with Java is like. 
    
  * [Genus](https://www.cs.cornell.edu/projects/genus/)
    * A language expounding upon the ideas of JavaGI. 

## Haskell

  * [Learn You a Haskell For Great Good](http://learnyouahaskell.com/)
    * Maybe somewhat outdated, but a very good and gentle introduction to the language. Also, it's free to read online, so you have no excuse!
    
  * [A Purely Functional Typed Approach to Trainable Models](https://blog.jle.im/entry/purely-functional-typed-models-1.html)
    * A very intuitive introducion to the concepts behind machine learning, introduced in Haskell! Shows how many different types of machine learning models (such as RNNs) can be understood in terms of common functiona programming constructs.
    
  * [Neural Networks, Types, and Functional Programming](http://colah.github.io/posts/2015-09-NN-Types-FP/)
    * Another post on deep learning in Haskell. For a whole awesome list of stuff like this, see [here](https://github.com/austinvhuang/awesome-haskell-deep-learning). 

## Kotlin

  * [Kotest](https://kotest.io/)
    * Very nice testing framework for Kotlin, supporting everything from property-based to non-deterministic testing.

  * [Arrow](https://arrow-kt.io/)
    * Collection of utilities for functional programming in Kotlin -- including support for optics.
    
  * [Http4k](https://www.http4k.org/)
    * Simple HTTP framework based on the idea of a server request/response handler as a function.
    
  * [KotlinGrad](https://github.com/breandan/kotlingrad)
    * Type-safe automatic differentiation in Kotlin.

## Rust

# Math

## Category Theory Papers

  * [Towards a Common Categorical Semantics for Linear-Time Temporal Logic and Functional Reactive Programming](https://dl.acm.org/doi/10.1016/j.entcs.2012.08.015) [(talk)](https://kodu.ut.ee/~varmo/tday-nelijarve/jeltsch-slides.pdf)
    * The curry-howard correspondant of LTL (linear-time temporal logic) is functional reactive programming. 

  * [The Continuity of Monadic Stream Functions](http://www.cs.nott.ac.uk/~psxjf/monadic-continuity.pdf)
    * Compare with the above. Another really interesting connection between FRP (monadic stream functions) and Brouwerian ideas. 

## Math History

  * [Richard Montague: The simplicity of language, the complexity of life](https://www.richardmontague.com/)
    * Sample from a WIP biography being written of Richard Montague. 
