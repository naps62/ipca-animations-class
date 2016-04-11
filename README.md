# Animation exercises

## Setup needed

If you already have a web development environment you can use (such as an existing web project), go for it.
If not, there's no need to spend time installing anything or setting up a page for testing. Use [Codepen](http://codepen.io/pen/) to get started right away.

## 1. CSS Transitions

**Goal:** [Text Input Effects](http://tympanus.net/Development/TextInputEffects/)

Choose one of the input effects on the above link, and try to mimic it as closely as possible.
The style itself (colors, sizes, fonts) can be your own if you want. We're only concerned with the animation effect itself

Steps:

1. Don't worry about transitions for now. Create a static input with the appropriate style: label, colors, font, spacings
2. Design the state of the input when the cursor is on (i.e.: when it is focused). This should correspond to how your input should look like after the transition
3. Apply the transition properties to make your element move from one state to another

**Bonus:** If you fill in the input, and unfocus it, does it keep the end state? Should it? How can you achieve that?


## 2. CSS Animations

**Goal:** [Animated Atom](http://codepen.io/naps62/full/MwVRXZ/)

Some of effects here are probably too complex for the time we have, so let's stick with a toned down version.

1. Create an atom, with a nucleus in the middle, an orbit around it, and 2 or 3 electrons on top of that orbit
3. Make the electrons spin around the nucleus, over the orbit.
4. Give each electron a different speed.
2. Add a glow effect to both the nucleus and the electrons (with a shadow, an image, or even a new element with opacity around it. It's up to you)

**Bonus:** Think about how you could achieve the final 3d effect. How would you do it?

## 3. JS Animations

**Goal:** Moving square

Create a square that you can control by moving in all four directions. Use any animation library you prefer (recommended: jQuery or Velocity.js)

1. Create a small square in the center of your page
2. Add four buttons somewhere, one for each direction
3. Whenever one of the buttons is clicked, the square must move 50px in the corresponding direction.
4. The movement must be animated, with a non-linear Easing

**Bonus:** Remove the buttons, and listen to keyboard events from the arrow keys.
**Bonus 2:** Instead of moving 50px every time, keep the square moving at a constant speed while the button or arrow key is being pressed


## 4. JS 3rd Party libraries

**Goal:** [Rubyconf PT 2014's website](http://2014.rubyconf.pt).

1. Grab the necessary images ([foreground](http://2014.rubyconf.pt/images/foreground.svg), [mountains](http://2014.rubyconf.pt/images/mountains.svg), [clouds](http://2014.rubyconf.pt/images/clouds.svg), [sky](http://2014.rubyconf.pt/images/sky.svg))
2. Set them up in a page, placing them in the correct position.
2. Include [parallax.js](https://github.com/wagerfield/parallax) in your page
3. Apply the parallax effect. Follow the [library's README](https://github.com/wagerfield/parallax) for instructions.
