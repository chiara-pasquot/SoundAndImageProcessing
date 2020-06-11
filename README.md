# SoundAndImageProcessing

For the final assignment for  'Computational Practices: Sound and Image Processing', I created five small projects in p5.
Each project focuses on a different lesson, trying to include all the topics that I most enjoyed during this semester.

<h2>Project 1</h2>

I decided to base my first project on the information learnt during the initial lesson of 'Sound and Image Processing'.
During the first lesson, we discovered how to manipulate the pixels array (with the loadPixels function), and we added colour to our canvas using this technique; my project takes inspiration from these examples, but to make the design more interactive I decided that the colour should vary.
The first and the last pixels, indexed 0 and 3, are set to a random number (this gives a 'white noise' effect to the canvas), on the other hand, the pixels indexed in first and second position, are set to vary depending on the X and Y position of the mouse. 
I believe this project could be an excellent idea for an installation to use with non-guided meditations and intuitive chromotherapy.

<h2>Project 2</h2>

This project takes inspiration from our lessons on filters, more specifically the section about vignettes;  since this is technically not a filter, I decided to use this technique for a different purpose.
Instead of filtering a picture for an artistic approach, I decided to use this method to create a little game; the rules are simple, you must find Waldo! Inspired by the popular children's game, and using an original 'Where's Waldo' board, this project uses an interactive vignette to help the player find the character.
The vignette, in this example, is used as a torch to illuminate the drawing.

<h2>Project 3</h2>

This project uses the information learnt in our recursion lesson.
To create this design, I started from the base of the tree, creating a line at the bottom of the canvas and giving it a set thickness. After using translate() to set the next point to start from the end of the line, I built a function that would create a new line smaller and with an angle on the left and right side of the previous line. 
The new function will run until the last branch is smaller than 2.  I also decided to change the colour and thickness of the lines as they are becoming smaller, to keep the drawing more realistic. 
I enjoyed creating this project, and I think it can have multiple uses in many different designs.

<h2>Project 4</h2>

I decided to base my fourth project on the particle system lesson.
Although the concept might seem simple, it is an interesting theory, and I enjoyed working with it.
The project uses the particle system to recreate some artificial constellations. Each drawn ellipse has a randomly assigned diameter, between 6 and 13 pixels, and colour.
The particles are freely moving in the canvas, bumping off its borders, and can interact with each other when they are closer than 80px with another ellipse.
I set the background to be a dark blue, to make this starry sky even more realistic.

<h2>Project 5</h2>

The final project takes inspiration from the lesson about convolution and kernels. I decided to use an edge detective kernel to process my image:

[-1, -1, -1],

[-1, 8, -1],

[-1, -1, -1]

This type of kernel will increase the pixels that are very different from the neighbouring ones and will decrease the pixels that are very similar to the next ones.
Since this type of kernel works best with a picture with high contrast, I decided to choose one of Klimt's painting to use as a base image.
My favourite painting from Klimt is Judith I, and this is the picture I used for the fifth project.
I think the final result of this project is perfect and the colours of the painting, although mutated, they are still vibrant and bright.






