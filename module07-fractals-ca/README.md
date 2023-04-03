# Fractals and Cellular Automata

## Core Material

For each module, I will provide written and video tutorials on the topics. You can review whichever format suits you best. If the amount feels overwhelming, please reach out and we can help you narrow things down, and select a subset of the material to focus an exercise around. It's a lot!

### Cellular Automata

- 📗 [Chapter 7](https://nature-of-code-2nd-edition.netlify.app/cellular-automata/)
- 🚂 [Game of Life Coding Challenge](https://thecodingtrain.com/CodingChallenges/085-the-game-of-life.html) - 38 min

### Fractals

- 📗 [Chapter 8 Fractals](https://nature-of-code-2nd-edition.netlify.app/fractals/)
- 🚂 [Recursion Coding Challenge](https://thecodingtrain.com/CodingChallenges/077-recursion.html) - 12 min
- 🚂 [Fractal Tree Coding Challenge](https://thecodingtrain.com/CodingChallenges/014-fractaltree.html) - 15 min
- 🚂 [Fractal Tree with Objects](https://thecodingtrain.com/challenges/15-object-oriented-fractal-trees) - 22 min

### Code Examples

- 💻 [Fractal and CA code examples from videos](https://editor.p5js.org/codingtrain/collections/fJ78Clagf)
- 💻 [CA code examples from Chapter 7](https://editor.p5js.org/natureofcode/collections/vO150fv4lv)
- 💻 [Fractal code Chapter 8](https://editor.p5js.org/natureofcode/collections/ujbdOAEy3)

### Reference Research and Artistic Work:

- [MATHEMATICAL GAMES: The fantastic combinations of John Conway's new solitaire game "life"](http://ddi.cs.uni-potsdam.de/HyFISCH/Produzieren/lis_projekt/proj_gamelife/ConwayScientificAmerican.htm) by Martin Gardner, Scientific American 223 (October 1970)
- [Parable of the Polygons](https://ncase.me/polygons/) by Nicky Case and Vi Hart
- [The Game Of Life - Emergence In Generative Art](https://www.artnome.com/news/2020/7/12/the-game-of-life-emergence-in-generative-art)
- [The Fractals at the Heart of African Designs](https://www.ted.com/talks/ron_eglash_the_fractals_at_the_heart_of_african_designs?language=en#t-4262)
- [Fractals in Thai Cultural Designs](https://kvis.ac.th/userfiles/files/Fractals_full%20paper-corrected.pdf)
- [“Fractal Expression” in Chinese Calligraphy ](https://arxiv.org/pdf/0810.1242.pdf)

## Supplemental Material

For each module, I will provide a list of additional video tutorials and readings that you may draw on for further exploration. It's unlikely you would be able to consume everything in one week and if you are looking for guidance about what might fit with your interests and learning style the most, please reach out.

- 🚂 [All Coding Train Fractal Videos](https://thecodingtrain.com/challenges/lang/all/topic/fractal))
- 📕 [The Algorithmic Beauty of Plants](http://algorithmicbotany.org/papers/#abop)

### Assignment

For this week's exercise pick one of the above examples to serve as the foundation of your assignment. It can any of the fractal or CA examples, or a related aglorithm you find through your own research. Create your own version of the algorithm, and iterate variations on the idea by exploring custom visual design elements or rule adjustments. Below is a long list of ideas to explore for CA and Fractals.

#### CA

1. Consider Non-rectangular Grids. There’s no particular reason why you should limit yourself to having your cells on a rectangular grid. What happens if you design a CA with another type of shape, e.g. triangle, hexagon, etc.
2. Probabilistic. The rules of a CA don’t necessarily have to define an exact outcome, for example with the Game of Life, what if a cell as an 80% chance of turning on based on its neighbors.
3. Continuous. For the examples this week the cell's state can only be a 1 or a 0. What if the cell’s state was a floating point number between 0 and 1?
4. Image Processing. Many image-processing algorithms operate on CA-like rules. Blurring an image is creating a new pixel out of the average of a neighborhood of pixels. Simulations of ink dispersing on paper or water rippling over an image can be achieved with CA rules. Try implementing a CA where a pixel is a cell and a color is its state.
5. Historical. What if a cell can track its history: how long it has been a 0 or 1. How might you visualize this. How could it adapt and change its rules over time by learning from its history?
6. Moving cells. In these basic examples, cells have a fixed position on a grid, but you could build a CA with cells that have no fixed position and instead move about the screen. What CA rules were applied to flocking boids?!
7. Nesting. Another feature of complex systems is that they can be nested. Our world tends to work this way: a city is a complex system of people, a person is a complex system of organs, an organ is a complex system of cells, and so on and so forth.

#### Fractals

1. Stochastic: What if each step of fractal recursion involves some level of randomness. For example, what is each branch of a tree has a random number of sub-branches? What if the angles are random?
2. Oscillation / Noise: Can you apply oscillating motion or Perlin noise to the properties of a fractal. For example, can a Fractal tree "sway"?
3. What designs can you create by varying the visual quality of each subsequent generation of fractal recursion? For example with the `strokeWeight()` for each branch, a tree could have a thick root with subsequently thinner branches.
4. In what ways could the physics algorithms from modules 1-5 be applied to a fractal shape?

## Emoji Key

The following emoji key will hopefully help you navigate the material for each module.

- 🚂 Video tutorial from Coding Train
- 🎥 Other video tutorial
- 📗 Nature of Code book
- 📕 Other reading
- 💻 Code examples
- 🎨 Creative project references
