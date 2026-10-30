### Describe how you implemented the timer and how you generated random colors. Why is it important to use a consistent interval for the lighting?

I created a function that randomly generated colors by picking random numbers through a number generator then puting those numnbers into a set background and because colors are picked through a assortment of a certain numbers once all the random numbers got put together a color was generated. after that in order to keep the numbers changing I put the function into a setinterval which ran the function every 1500 milliseconds to keep the colors changing.

Explain the concept of “event bubbling.” How did stopPropagation() allow you to separate the Dancer’s interaction from the Floor’s interaction?

Because both the dancer and the floor uses on click events and because the dancer is inside of the dance floor it is the parent of the dancer and will also change on the onclick event. Stopping propogation stops the dance floor from reacting when you click the dancer emoji.