# Neural Style Transfer
This is a tensorflow implementation of the paper: [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576.pdf) by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge.

The paper presents an algorithm for combining the content of one image with the style of another image using convolutional neural networks. 

## How does it work?
In this algorithm, we define two distances namely the Content Distance(D_c) and the Style Distance(D_s).

**Content Distance**: It measures that how different is the content between the original image and the output image of the algorithm.
**Style Distance**: It indicates how different are the output image or feature map and the style image.
We take a third image ie the input and we transform it in order to both minimize its D_c with Content Image and D_s with Style Image.

## Examples
### The Scream - Edvard Munch
<img src="/images/football.jpg" width="320" height="300"> <img src="/images/The Scream.jpg" width="320" height="300"> <img src="/images/Football_Scream.jpg" width="320" height="300">

### La Reve - Picasso
<img src="/images/pyramids.jpeg" width="320" height="300"> <img src="/images/La Reve.jpg" width="320" height="300"> <img src="/images/pyramids_La_Reve.jpg" width="320" height="300">

### Udnie - Francis Picabia
<img src="/images/scene.jpg" width="320" height="300">  <img src="/images/Udnie.jpg" width="320" height="300"> <img src="/images/scene_Udnie.jpg" width="320" height="300">
