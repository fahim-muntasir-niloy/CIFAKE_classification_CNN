# CIFAKE: Real and AI-Generated Synthetic Images Classification using CNN

The quality of AI-generated images has rapidly increased, leading to concerns of authenticity and trustworthiness. CIFAKE is a dataset that contains 60,000 synthetically-generated images and 60,000 real images (collected from CIFAR-10).

## Dataset details
The dataset contains two classes - REAL and FAKE.
For REAL, we collected the images from Krizhevsky & Hinton's CIFAR-10 dataset
For the FAKE images, we generated the equivalent of CIFAR-10 with Stable Diffusion version 1.4

There are 100,000 images for training (50k per class) and 20,000 for testing (10k per class)

## References
[CIFAR10] Krizhevsky, A., & Hinton, G. (2009). Learning multiple layers of features from tiny images.

[CIFAKE] Bird, J.J., Lotfi, A. (2023). CIFAKE: Image Classification and Explainable Identification of AI-Generated Synthetic Images. arXiv preprint arXiv:2303.14126.

*Real images are from Krizhevsky & Hinton (2009), fake images are from Bird & Lotfi (2023). The Bird & Lotfi study is a preprint currently available on ArXiv and this description will be updated when the paper is published.*