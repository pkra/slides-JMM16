

# Notes


## Slide 1: What is MathJax

* go through slide
* Show of hands: who knows what MathJax is?
  * Sorry for wasting your time then!

## Slide 2: Who is MathJax

* go through slide
* point out team

## Slide 3: The web as a new medium

* tell the story

## Slide 4: The web as a new fabric

[* add example: slides rendering vs struik]

* the digital age will revolve around the web
* like any new medium, the first focus ended up being on imitating the old
* The web was very crude
  * so people had to get creative (and could!)
* HTML5 JS etc completed the imitation phase
  * now the most universal medium ever
* In the past few years, the search for the web's own grain.
* Some examples
  * Advent of responsive design earliest example perhaps, exploring the web's fluidity
  * Merging of media
    * text, audio, video merging => Youtube, Hannover project in this session,
    * Computation, visualization, interactivity: Sage Math, IPython/Jupyter, mathJS, maximaJS
* more to come
  * Virtual reality (Vi Hart, MathBox)
* search for the grain not just about standards, more orthogonal
  * looking beyond standards
  * looking into the new (possible) practices
* For Math: MathML only
  * falls short in many regards
  * overwhelming print focus => supposed Knuth quote
  * not adopted by browser vendors, only a few volunteers working without contact to standards bodies
  * not aligned with other standards
  * slowly becoming unnecessary due to improvements in the OWP
* For science: nothing much.

## Slide 5: The Semantic Enrichment project I

* Funded by the Alfred P. Sloan Foundation
* MathJax's internal format is Presentation MathML
  * but shortcomings are growing
  * we want to preserve the good parts and expand on them.
* Presentation MathML is too weak, Content MathML is too strict
* Enriching for what? The grain!
  * fluidity: new form of rendering in the fluid web -- responsive equations
  * universality:  working towards making any math rendering universally useful
    * navigation/exploration
    * voicing for accessibility

## Slide 6: The Semantic Enrichment project II

* Two ways for enriching P. MathML. procedural and declarative (grammatik)
  * chose procedural since it should always produce something
* Goal: Enriching the presentation -- not the "real" semantics


## Slide 7: Time for demos

* Prep struik beforehand
* only show sample
* try demo the walker


## Slide 8: What we learned about usability

*  MathJax always wanted to make itself superfluous.
  * Solve the chicken&egg problem of MathML.
* MathML in browsers failed
  * How can we achieve it now?
* Bottom up: start where the technology is today.
  * MathJax, jqmath, mathquill, KaTeX
  * improve its usablity.
* Long term game
  * no more special requests for math
  * if it doesn't improve the OWP, it's wrong.
* ARIA:
  * separating semantic from presentation
    * semantics of presentation would be a good start => cf. Knuth quote
  * Because whatever new forms of math will come up in the search for the grain, and however these will render, we'll need to convey meaning flexibly.
* CSS
  * Because whatever math has to offer in terms of layout, (spoiler: it ain't much these days), those features must be universal and not just math-only (as in MathML).
  * For a while, I thought CSS would be the way in. Math layout adds lots of interesting and powerful layout features.
  * But math ain't the special. And we shouldn't pretend it is.

* Cf. life cycle of HTML
  * first very strict elements
  * then div/span soup with CSS
  * now we're back to a better

## Slide 9

* reflection on the session title
  * don't look for today's web.
  * Back to the movable type comparison
  * whatever the math in the digital age will look like, the web will be the central medium. We need to explore what math on the web will eventually mean and build infrastructure to accommodate that.
