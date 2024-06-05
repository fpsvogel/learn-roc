<!-- omit in toc -->
# Learn functional programming: a Rubyist's list

Hi! I'm on a journey to learn functional programming (FP). Won't you join me?

If you notice any broken links here, please let me know by [opening an issue](https://github.com/fpsvogel/learn-functional-programming/issues/new).

This is not meant to be an exhaustive list of FP resources, only my path to learning some FP and applying it to Ruby.

<!-- omit in toc -->
## Table of contents

- [Haskell](#haskell)
  - [Community](#community)
  - [Courses, etc.](#courses-etc)
  - [Exercises](#exercises)
  - [Make a CLI game](#make-a-cli-game)
  - [Applications](#applications)
  - [Dependent types, type theory](#dependent-types-type-theory)
  - [More resources](#more-resources)
- [Elixir](#elixir)
  - [Courses, etc.](#courses-etc-1)
  - [Exercises](#exercises-1)
  - [Community](#community-1)
  - [More resources](#more-resources-1)
- [FP in Ruby](#fp-in-ruby)
  - ["Functional lite": prefer immutability and avoid side effects](#functional-lite-prefer-immutability-and-avoid-side-effects)
  - [Hanami/dry-rb ecosystem](#hanamidry-rb-ecosystem)

## Haskell

### Community

- [Functional Programming Discord server](https://discord.com/invite/K6XHBSh)
- [Haskell - Community page](https://www.haskell.org/community/)

### Courses, etc.

- [x] [Try Haskell](https://tryhaskell.org)
- [ ] [Haskell MOOC](https://haskell.mooc.fi/) and exercise solutions ([1](https://github.com/tinfoil-knight/haskell-mooc), [2](https://github.com/mikkom/haskell-mooc/tree/master/exercises), [3](https://github.com/dandax123/haskell-mooc-solutions))
- [ ] [Wikibooks - Haskell](https://en.wikibooks.org/wiki/Haskell)
- [ ] [Haskell for Imperative Programmers](https://www.youtube.com/playlist?list=PLe7Ei6viL6jGp1Rfu0dil1JH1SHk9bgDV) (videos)
- [ ] [Implement With Types, Not Your Brain!](https://reasonablypolymorphic.com/blog/typeholes/)
- [ ] 💲[Soar with Haskell](https://www.amazon.com/Soar-Haskell-beginners-functional-programming/dp/1805128450)
- [ ] 💲[Haskell Programming From First Principles](https://haskellbook.com/)
- [ ] [thoughtbot - Maybe Haskell: Programming without Null](https://github.com/thoughtbot/maybe_haskell)
- [ ] [The Haskell Phrasebook](https://typeclasses.com/phrasebook)
- [ ] [Typeclassopedia](https://wiki.haskell.org/Typeclassopedia)
- [ ] 💲[Effective Haskell](https://pragprog.com/titles/rshaskell/effective-haskell/)
- [ ] 💲[Haskell (almost) Standard Libraries](https://leanpub.com/haskell-stdlibs)
- [ ] 💲[Haskell in Depth](https://www.manning.com/books/haskell-in-depth)

### Exercises

- [ ] [Exercism - Haskell](https://exercism.org/tracks/haskell)
- [ ] [HackerRank - Functional Programming track](https://www.hackerrank.com/domains/fp)
- [ ] [nested-map-reduce-traversal challenge](https://github.com/josevalim/nested-map-reduce-traversal) ([discussion](https://discourse.haskell.org/t/beautiful-functional-programming/7411), [Haskell solutions](https://github.com/josevalim/nested-map-reduce-traversal/tree/master/haskell), more Haskell solutions: [1](https://gist.github.com/TristanCacqueray/fc8fb5cbba7a0391341e73b80a90b2e8), [2](https://gist.github.com/goldfirere/ed1450872afd324ed656e2807b8dfcc0), [3](https://github.com/danielc777888/toy-problems/blob/main/nested-map-reduce-traversal/Recursion.hs), [4](https://gist.github.com/lazamar/305e8808f8975258f6acea4d20fd3405))

### Make a CLI game

- **Guides:**
  - [ ] <http://jackkelly.name/blog/archives/2022/05/28/text-mode_games_as_first_haskell_projects/index.html>
  - [ ] <https://medium.com/codex/developing-a-video-game-in-haskell-e8259050e4dc>
  - [ ] <https://whatthefunctional.wordpress.com/2018/03/07/making-a-text-adventure-in-haskell-part-1/#comments>
  - [ ] <https://www.youtube.com/watch?app=desktop&v=WLYN7sUDm7Y>
  - [ ] <https://haskell-via-sokoban.nomeata.de/>
- **Examples:**
  - "Haskell Program to Play the Blackjack Card Game" in [Haskell Tutorial and Cookbook](https://markwatson.com/opencontent/haskell-cookbook.pdf)
  - <https://codereview.stackexchange.com/questions/159069/haskell-text-adventure-game>
  - <https://github.com/emanuelfakh/Game_Haskell>
  - <https://github.com/rklyne/haskell-text-adventure>
  - <https://github.com/jensdanb/Pong2>
  - <https://github.com/jasonstolaruk/CurryMUD>

### Applications

- [ ] [Obelisk](https://github.com/obsidiansystems/obelisk) is a web app framework in which the front end is written in Haskell too.
- [ ] [IHP](https://ihp.digitallyinduced.com/) or [Yesod](https://www.yesodweb.com/) are more traditional web app frameworks.
- [ ] [Pandoc](https://github.com/jgm/pandoc) as an example project outside of web dev.

### Dependent types, type theory

- [ ] 💲[Type-Driven Development with Idris](https://www.manning.com/books/type-driven-development-with-idris)
- [ ] [Agda Wiki](https://wiki.portal.chalmers.se/agda/pmwiki.php)
- [ ] [agda2hs](https://agda.github.io/agda2hs/)
- [ ] [Learn You an Agda](http://learnyouanagda.liamoc.net/pages/introduction.html)
- [ ] 💲[Verified Functional Programming in Agda](https://dl.acm.org/doi/book/10.1145/2841316)
- [ ] [Programming Language Foundations in Agda](https://plfa.github.io/)
- [ ] 💲[Types and Programming Languages](https://www.cis.upenn.edu/~bcpierce/tapl/)

### More resources

- [awesome-learning-haskell](https://github.com/tweag/awesome-learning-haskell)
- ["Resources" section in The Haskell Guide](https://haskell-docs.netlify.app/resources/resources/)
- [Haskell Books](https://www.extrema.is/articles/haskell-books)

## Elixir

### Courses, etc.

- [ ] [Elixir School](https://elixirschool.com/en)
- [ ] [The Soul of Erlang & Elixir](https://www.youtube.com/watch?v=JvBT4XBdoUE)
- [ ] [DockYard Academy curriculum](https://github.com/DockYard-Academy/curriculum)
- [ ] 💲[Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers-2)
- [ ] 💲[From Ruby to Elixir](https://pragprog.com/titles/sbelixir/from-ruby-to-elixir)
- [ ] 💲[Phoenix on Rails](https://phoenixonrails.com/) ($10 discount code [here](https://elixirforum.com/t/phoenix-for-rails-developers/54624/18))
- [ ] 💲[Elixir in Action](https://www.manning.com/books/elixir-in-action)

### Exercises

- [ ] [Elixir Koans](https://github.com/elixirkoans/elixir-koans)
- [ ] [Exercism - Elixir](https://exercism.org/tracks/elixir)
- [ ] Build a [SpaceTraders](https://spacetraders.io/) Phoenix app

### Community

- [ ] [Elixir Status](https://elixirstatus.com/)

### More resources

- ["Learning" page on the Elixir site](https://elixir-lang.org/learning.html)

## FP in Ruby

### "Functional lite": prefer immutability and avoid side effects

- [Avoid Mutation — Functional Style in Ruby](https://www.rubypigeon.com/posts/avoid-mutation-functional-style-in-ruby/)
- [Boundaries](https://www.destroyallsoftware.com/talks/boundaries)
- Sandi Metz ([source](https://dev.to/sandimetz/comment/255m)): "I only have a small bit of experience with functional languages, so I don't get to have much of an opinion. I can say, however, that immutability and no side-effects are great ideas, and that I've borrowed them for my OO. My initial goal for every new object I write is that it not change, and that it not have side effects. This obviously can't suit every object, but I've been pleasantly surprised about how much can be done under these constraints, and how much the constraints simplify code."
- Avdi Grimm ([source](https://web.archive.org/web/20201009182546/https://github.com/yct21/observatory/issues/93)): "Functional programming ideas about preferring immutability and isolating interactions with the outside world can help us avoid the worst pitfalls of procedural and object-oriented coding. But trying to program in a *'fully FP'* style in Ruby can be like paddling a kayak with a canoe paddle. Upstream. […] Your best bet for effective development is to learn to 'code with the grain' [of the language you're using]. And when you get right down to it, Ruby's grain is object-oriented."

### Hanami/dry-rb ecosystem

- [This blog series by Tim Riley](https://www.icelab.com.au/notes/conversational-rom-rb-part-2-types-associations-and-update-commands) is a good introduction. The linked article is the last one; scroll to the bottom to see a list of all the posts in the series.
- Learn the [Hanami](https://hanamirb.org/) framework with [Hanami Mastery](https://hanamimastery.com) and example apps found in GitHub repo searches ([1](https://github.com/search?q=hanami+example+pushed%3A%3E2022-01-01&type=repositories), [2](https://github.com/search?q=hanami+app+pushed%3A%3E2022-01-01&type=repositories), [3](https://github.com/search?q=hanami+application+pushed%3A%3E2022-01-01&type=repositories), [4](https://github.com/search?q=hanami+software+pushed%3A%3E2022-01-01&type=repositories)).
- Explore [dry-rb](https://dry-rb.org/) gems.
