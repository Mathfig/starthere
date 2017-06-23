# River & Lake Detection

## Project description:

#### Problem:
  Build functions that take a satellite image and output the same image but with the boundaries of the rivers or lakes highlighted.

#### Outline of approach:
  * Cut the initial image into smaller sections and train a neural network with the sections which contain rivers or lakes. 
  * Then the highlights will only be appplied to objects which the neural network deems to be a river or lake
  * Use image filter functions to isolate the rivers or lakes and use edge detection to pick out the outlines which we can then highlight
  * After isolating the highlights, we can overlap the original image with the new one to create a satellite image where the boundaries of all the rivers or lakes are highlighted

#### Extra Challenge Problems:
  * Match the river or lake image to its name
  * Generate random rivers and lakes based on the images that the neural network was fed
