# Variational autoencoders

Train a variational autoencoder to encode images into a normal distribution vector and decode samples from those distributions to the image (regular VAE training). Use CNN layers.
The following is the main part of the assignment:

- Train a VAE to fit data onto 4-10 distributions (choose 1 of the values in that range) which is the setting of distribution’s vector length (for example 6 means 6 * (Mean, Std [sigma]).
- Apply the model on test images.
- Make a report gathering all generated images and all your results with comments.
- Make a GUI with a slider, this GUI will be used after you have a trained model. After training the model, let the user choose through the GUI and the slider how many images to randomly generate (If I set it to 5 it generates 5 images). Make the slider be able to take values from 1 to 12. The process of generating an image is done through sampling the distributions and decoding those samples.

__________________________________ 
<b>Dataset</b>

- Dataset consists of at least 50 custom images. You cannot use a ready dataset; all images should be gathered (You can take photos or download images through searching).
- Image size should be between 64 and 128. You can choose any number in that range but be sure that the images are identifiable at that resolution (If we look at the image, we can somewhat tell what’s in it) and I don’t think lower than 64 is identifiable.
- Try to have some variety in the images. Beware of underfitting in the results.
