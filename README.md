# Improved Generative Models through Topological Data Analysis


# Abstract: 
Generative Adversarial Networks have made signifcant progress in the
field of image generation, but they have serious downsides including train
ing diffculties due to mode collapse. We propose two novel solutions based
on persistence homology, a method from the field of topological data analysis, 
in an attempt to generate better quality images and reduce training
difficulty. The first being incorporating topological information into the
loss function of the generator network. The second solution is implementing
a new topological layer into the discriminator network. We present
and compare the results of these two techniques against a baseline GAN
trained with the standard architecture all trained on the MNIST hand-written
digit data set. Our results show that adding a topological loss
function both improves performance and training speed, while adding a
topological layer hurt both performance and training speed.
