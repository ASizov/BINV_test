# BINV_test

The task is to create and implement a GAN that is based on AttnGAN and somehow uses the text encoding module from the paper A Generative Adversarial Approach for Zero-Shot Learning from Noisy Texts (so the images are now generated given input words and noise-reducing encoding of the input sentence presented in the paper).

As it is stated in the paper the text embedding is first passed through a fully connected (FC) layer to reduce the dimensionality. Then it is shown how this additional FC layer has a critical contribution to noise suppression. 

So the main part of noise reduction is this additional FC layer, and it was put into the model.py prior to words processing with AttnGan procedure. Hope this description would help.
