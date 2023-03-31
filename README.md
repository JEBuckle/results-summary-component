## My process

I started by building the left result card first, I created the layout of the items using flex, to make it easier centering everything. Had to play around a bit with padding to make it look relatively similar to the design picture. After creating the first result card, I had to rethink how to create a layout in which I can display both 'Cards' (results, summary) next to each other, and ended up creating a grid-layout that has two columns on one row. Styling and positioning the elements within the 'Summary' component really was the hardest part, as I have no real prior experience on how to create such components.
I ended up creating a grid-layout with 3 columns, one for the icon, one for the 'class-title' and one for the score. This made it easier to align the items vertically, as they weren't symmetrically aligning by themselves (the class-title components alligned from the bottom of the div, and the score aligned from the top of the div - I have not found out why, but fixed it with padding-top). I played around with both flex and grid for this card-component, and eventually managed to somewhat re-create the design with the above method, this led to the unfortunate realization that it is practically impossible to implement the 'background-color' for the 4 individual class-title components.

After managing to style the component cards properly, I got stuck at optimizing this layout for mobile, and haven't figured out how to properly do so just yet - nonetheless I wanted to publish this first draft of my challenge, as I am very interested to see how other people tackled this challenge.

## Things that I have learned:

- It is important to plan ahead -> I went into the challenge and began creating the first component, without planning on how to create the second card component, instead I should have planned the layout from the get-go.-> This is true for individual elements too, I realize that my code is extremely nested (for how few elements I'm actually presenting) and wonder how this could be done in a more elegant way.
- creating gradients using the hsla() function
- how to use the grid-column/row systems
- implementing flexbox within grid elements to make styling easier

## New Commit:

## This is my second version of the challenge.

## In this version I completeley changed the layout & styling - headers are now aligned properly and the code is less messy.

## Mobile optimization is not fully completed just yet, this version is rather a complete refactor of the main code & css -> mobile optimazion coming
