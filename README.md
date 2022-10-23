# Nate's Awesome List

![Awesome](https://awesome.re/badge.svg)

My own personal [awesome list](https://github.com/sindresorhus/awesome/blob/main/awesome.md) in a variety of topics.

# Software Engineering

  * [A Few Thoughts About Path Coverage](https://blog.regehr.org/archives/386)
    * Some interesting thoughts on what it means for a code-base to really be thoroughly unit-tested.
    
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
    * I don't know if this is may favorite GUI framework, and it's definitely not the easiest to use (whether or not it _could be_ with more polish, I'm not sure) -- but just for the experience of learning it (like many people say about learning Haskell itself), I'd reccomend playing around with this. It will change the way you think about reactive programming and GUI development. I can say in my experience it has taught me how to use more mainstream frameworks like Kotlin flow more effectively.
    
 * [Purescript Refract](https://github.com/pkamenarsky/purescript-refract)
   * An interesting variation on TEA (The Elm Architecture) making good use of lenses to compose components. Indigo does something similar.

# CS Papers

  * [The Optics of Language Integrated Query](https://arxiv.org/abs/2009.00997)
    * Fascinating and really expressive API for a query language, based on optics. Almost reminds me of GraphQL -- I wonder if there's a relationship worth persuing there.

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

## Haskell

  * [Learn You a Haskell For Great Good](http://learnyouahaskell.com/)
    * Maybe somewhat outdated, but a very good and gentle introduction to the language. Also, it's free to read online, so you have no excuse!

## Kotlin

## Rust

# Math

## Math History

  * [Richard Montague: The simplicity of language, the complexity of life](https://www.richardmontague.com/)
    * Sample from a WIP biography being written of Richard Montague. 
