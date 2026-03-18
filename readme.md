Attempt to create the smallest possible neural network that encodes the border at Baarle-Nassau.
Inspired by this WelchLab video: [https://www.youtube.com/watch?v=qx7hirqgfuU&t=266s](https://www.youtube.com/watch?v=qx7hirqgfuU&t=266s)

I used an approach that triangulates the Belgian part of the border and then does a line check for each triangle edge.
The line checks are encoded as neurons.

### Result

Network size: 5000 Neurons

We could get a lot smaller if we switch the triangle for a minimum set of convex polygons.
Then again, if we increase the resolution of the border, we will need more neurons again.

