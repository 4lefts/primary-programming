# Primary Programming

A static site for a scheme of work for primary schools teaching computer programming, using [Scratch](https://scratch.mit.edu).

This site is built with [eleventy](https://11ty.dev).
To build the site:
`npx @11ty/eleventy`
Or, to run a dev server:
`npx @11ty/eleventy --serve`

## Programming Scheme Notes – KS2 Scratch

_Predict, run, investigate, make_

Start with a high-quality example
Scratch notes:
Thing children need:

- Make accounts, log in, load and save work
- Making sprites/costumes – vector vs bitmap mode
- Navigating the interface
- Adding scripts to different sprites (and not the stage unless you mean to)

### Y3

- Sequencing events, animation – making things happen after a certain amount of time, in order, e.g:
  - traffic light,
  - rocket launch, move, start, stop, wait,
  - move the snail around the garden to get the leaves, avoiding the predators
- Conditionals – selection – move character around screen,
  - if touching colour stop?
  - if touching colour hide? If snake hits eggs, eat (hide) them. Add “enemies” (hide character if hit)

### Y4

- Introduction to variables
  - make “collect the xs” game – vars for score/time/lives – extend y3 unit 2.
  - extend "collect the xs" game to use enemies that also collect xs and therefore reduce score.
- Repetition and loops – continues from variables
  - make a timer (increment a var)
  - make a times tables counter (count up in 3s, 5s, etc) – can you count the first n square numbers? Cube numbers? Stop a loop at a certain point.
  - make stopwatch – start stop reset, design interface (increment by 0.1 seconds?)
  - animation loops – eg ball bounce up and down, rocket orbit planet (forward and rotate), boat going around an island

### Y5

- Speed, direction, coordinates
- Random numbers and simulations
  - random maths questions? (implement the y4 times tables screening check?)

### Y6

- More complex variables
- Object properties?
