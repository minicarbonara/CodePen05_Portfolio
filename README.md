# CodePen05 - Portfolio exercise

## What we're building

A fake portfolio page displaying webdev projects, or art projects, or serial killings, whatever. We're testing and tweaking, as ever, on [a CodePen instance](https://codepen.io/minicarbonara/pen/rNeeBQV).

## Requirements (per FreeCodeCamp's exercise)

- A "Welcome" section with an id of *welcome-section*
- With an `<h1>` element containing text
- With a height equal to the height of the viewport
- A "Projects" section with an id of *projects*
- Containing at least one element with class *project-tile*
- Containing at least one link to a project
- A navbar with an id of *navbar*
- Attached to the top of the viewport, always visible
- Containing at least one link to a section of the page
- A link with an id of *profile-link* to a GitHub or FCC profile on a new tab
- At least one media query

The provided example is [this CodePen](https://codepen.io/freeCodeCamp/full/zNBOYG)

---

## What do we do about this

**WebDev is scrappy and so are we.** It's all trying to fit together a ton of different bits and pieces each working differently and many of them just copied from someone else's work without fully understanding how it's actually working. It feels like being a raccoon on a dumpster trying to assemble a moving car from pizza boxes and broken spark plugs.

So let's do just that. **Let's build a punk-ass portfolio for a raccoon that builds stuff using scavenged trash and he's not sure why it works but god damnit he made it.** It will have the worst colors, the ugliest type and will be like a spit in the eye of god.

BUT it will have nice, clean code underneath because we want to be anal about it.

## So what are the steps

### Phase 1. Figure out the *a e s t h e t h i c*
- Check out [stuff](https://artsqool.cool/) [that looks](https://www.shopsludgelife.com/) [or feels](http://donutcounty.com/) [like we are](https://knowyourmeme.com/memes/subcultures/jet-set-radio) [looking for](https://hotlinemiami.com/gate)
- Check out [colour palette webpages](https://www.colourlovers.com/) for a color selection. [This one, for example](https://www.colourlovers.com/palette/55400/Neon_Virus)
- Check out Google Fonts for a [Header](https://fonts.google.com/specimen/Pangolin) and [Paragraph](https://fonts.google.com/specimen/Fira+Mono) font pairing, plus one for [quotes](https://fonts.google.com/specimen/Swanky+and+Moo+Moo) or something
- Draw out [a crude wireframe](https://www.dropbox.com/s/dqprdqa6rwjg60r/portfolio_wireframe.jpg?dl=0) of the site's structure

### Phase 2. Set the basic elements
- Set the doctype, title, CSS link and such
- Create the sections with IDs: navbar, welcome, projects, contact and footer on HTML
- Create a sample *project-tile*
- Put the links on the *navbar* and link them to each section
- On CSS: give each section a *background-color* for blocking
- On CSS: set the font-family and fallbacks for `<h1>` to `<h6>` and `<p>`

### Phase 3. Style the basic elements
- Affix the *navbar* to the top of the viewport
- Create the `<h1>` on the Welcome section
- Set the Welcome section's height to 100vph
- Create whatever will support the project grid in the Projects section (CSS grid, flexbox, tables, you name it)
- Adjust the size and spacing of the *project-tile*, put some placeholder content on it
- Create the *profile link* on the Contact section, put some text about raccoons too
- Put a media query for viewports below 600px wide altering the project grid

### Phase 4. Optional testing and styling
- Create up to six project tiles to test the grid
- Play with hover animations on project tiles
- Play with gradients on the background to make it striped and fugly
- See how they do this cool smooth scroll when going to each section

### Phase 5. Finishing touches
- Update the *profile link*
- Put some cool logo on the *navbar*
- Run the FreeCodeCamp's test and hope for the best

