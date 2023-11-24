# NST_dashtoon
A basic Neural Style Transfer Algorithm using VGG19

  Following steps have been taken :
*   The original image, the style image and the generated image are all passed through the model and outputs are found out are all the output layers
*   The content loss which is the distance between the generated image and the content image is calculated.
*   The style loss which is the distance between the generated image and the content image is calculated using Gram Matrices.
*   The parameters are then optimized
