# Head-Rotation
This is a companion repository to the article "Head Rotation in Denoising Diffusion Models", joint work with Gabriele Colasuonno and Antonio Guerra.

<hr>
Denoising Diffusion Models (DDM) are currently at the forefront of cutting-edge technology in deep generative modeling. However, effectively exploring the underlying meaning in the latent space and identifying compelling paths for manipulating and editing important attributes of generated samples remains a challenge, mainly due to the high dimensionality of the latent space.

In this research, our focus is specifically on face rotation, which is recognized as one of the most complex editing operations. By utilizing a recent embedding technique for Denoising Diffusion Implicit Models (DDIM), we have achieved remarkable manipulations covering a wide rotation angle of up to $\pm 30^o$, while preserving the distinct characteristics of each individual.

Our methodology involves computing trajectories that approximate clusters of latent representations from dataset samples with various yaw rotations through linear regression. These trajectories are obtained by analyzing subsets of data that share significant attributes with the source image.

One of these critical attributes is the light provenance: as a byproduct of our research, we have labeled the CelebA dataset, categorizing images into three major groups based on the illumination direction: left, center, and right.

<hr>
