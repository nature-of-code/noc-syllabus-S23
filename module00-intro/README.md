# Introduction

Welcome to the class! This first module is about getting acclimated to the class. What coding language / environment would you like to use? Suggested is p5.js but you are welcome to create your assignments with any language or framework you like.

- [Introduction Slides](https://docs.google.com/presentation/d/1cQW-pC2c9kEFse-_g5KHol3DPVtHnHrlMuWKtwunjx4/edit?usp=sharing)

## Emoji Key

The following emoji key will hopefully help you navigate the material for each module.

- 🚂 Video tutorial from Coding Train
- 🎥 Other video tutorial
- 📕 Reading
- 💻 Code examples
- 🎨 Creative project references

## Core Material

For each module, I will provide written and video tutorials on the topics. You can review whichever format suits you best. If the amount feels overwhelming, please reach out and we can help you narrow things down, and select a subset of the material to focus an exercise around.

- 📕 [PDF: Introduction Draft Edition 2](https://drive.google.com/file/d/1G_16tPKByN9ya6l2Ws58X-OJK1yex9IX/view?usp=sharing)
- 🚂 [Introduction to Perlin Noise](https://youtu.be/Qf4dIN99e2w) - 11 min
- 🚂 [Perlin noise() vs. random()](https://youtu.be/YcdldZ1E9gU) - 10 min
- 🚂 [Graphing 1D noise](https://youtu.be/y7sgcFhk6ZM) - 13 min
- 🚂 [2D Random Walk](https://youtu.be/l__fEY1xanY) - 15 min

## Supplemental Material

For each module, I will provide a list of additional video tutorials and readings that you may draw on for further exploration. It's unlikely you would be able to consume everything in one week and if you are looking for guidance about what might fit with your learning style the most, please reach out.

### More about noise

- 📕 [Perlin Noise with p5.js](http://genekogan.com/code/p5js-perlin-noise/) by Gene Kogan
- 🚂 [2D Perlin Noise](https://youtu.be/ikwNrFvnL3g?list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM) - 11 min
- 🚂 [noiseDetail()](https://youtu.be/D1BBj2VaBl4?list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM) - 4 min
- 🚂 [Open Simplex Noise](https://youtu.be/Lv9gyZZJPE0?list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM)

### More about Random Walks

- 🚂 [Diffusion-Limited Aggregation](https://youtu.be/Cl_Gjj80gPE) - 47 min
- 🚂 [Random Walker with Vectors and Lévy Flight](https://youtu.be/bqF9w9TTfeo?list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM) - 16 min (note vectors will be explored in detail in Module 1)

### Code Examples

- 💻 [Nature of Code Introduction Example Collection](https://editor.p5js.org/natureofcode/collections/pKi2cbngG)
- 💻 [Additional Perlin Noise Example Collection](https://editor.p5js.org/codingtrain/collections/qTyT_RX11)
- 💻 [Basic Random Walk](https://editor.p5js.org/codingtrain/sketches/N-qqe1ExZ)
- 💻 [Diffusion Limited Aggregation](https://editor.p5js.org/codingtrain/sketches/XpS9wGkbB)
- 💻 [Random Walk Lévy Flight](https://editor.p5js.org/codingtrain/sketches/L24X90MBH)

## Assignment

Using the random walker as a model, develop a sketch that experiments with motion. Here are some ideas but you should feel free to develop your own.

- Use a random walker to "paint" colors.
- Try a walk in 3D, see [Quantum Cloud](http://en.wikipedia.org/wiki/Quantum_Cloud) for an example.
- Create a random walker with dynamic probabilities. For example, can you give it a 50% chance of moving in the direction of the mouse?
- Try implementing a [self-avoiding walk](http://en.wikipedia.org/wiki/Self-avoiding_walk). This one is really hard!
- Create a variation on the [a Levy Flight](http://en.wikipedia.org/wiki/L%C3%A9vy_flight).
- Create an array of `Walker` objects. Try adding a new object when you click the mouse.
- Use the random walker as a template to simulate some real-world "natural" motion. Can you develop a set of rules for simulating that behavior? Ideas: nervous fly, hopping bunny, slithering snake, etc. Consider the challenge of using minimal visual design, i.e. black and white primitive shapes. Can you give your "being" a personality? Can it express emotions -- happiness, sadness, fear?

Another way of thinking about the assignment is to apply the rules of motion to another medium of expression: sound, color, number, scale...

- Walk through RGB or HSB space (as opposed to XYZ)
- Walk through Pan, Amplitude, Pitch (as opposed to XYZ)
- Plot an "orchestra" of instruments on an XY plane and move a melody through it like.
- Create a constantly morphing creature shape using `createShape()` and `vertex()`. Play with how you change the number of vertices, anchor points.

### Instructions

- Document your work on the web with a short blog post. Here are some guiding questions if you are not sure what to write about:
  - What did you originally intend to create?
  - Narrate the process of creating your sketch.
  - What resources and examples did you draw on to create your sketch? What was most helpful / least helpful from this week’s materials.
  - What problems/discoveries did you encounter along the way?
- Submit a link to your blog post to the course Brightspace.
- Following the instructions in Brightspace, provide feedback on at least two other assigments.
