This GitHub repository contains the source code for paper "On stabilizing generative adversarial networks with adaptive noise injection,''
by Yamin Zhang, Fabing Duan, Francois Chapeau-Blondeau, and Derek Abbott, submitted to Physical Review E. The related codes are:

--------------------------------------------------------------------------------------------------------------------------
CGAN(四种激活函数+梯度范数图)20251109 .ipynb: A Jupyter Notebook exploring Conditional GANs using four different activation functions and plotting their gradient norm graphs.(not included in paper)

CIFAR 10 GAN GEU Cauchy supplement.ipynb: Supplementary experiments applying a GAN with a Generalized Exponential Unit (GEU) and Cauchy noise to the CIFAR-10 dataset. (CIFAR-10)

Fig 5 MInist GAN 3 activations.ipynb: Code to generate Figure 5, which compares the performance of three different activation functions on the MNIST dataset using a GAN.(MNIST)

Fig14-15 compare.ipynb: A notebook designed to reproduce and compare the experimental results shown in Figures 14 and 15 on MNIST dataset.(MNIST)

Fig14-15compare.ipynb: An alternate or updated version of the notebook used for comparing the results of Figures 14 and 15 on MNIST dataset.(MNIST)

Fig2-4 GAN改P=1000-2026.ipynb: A modified GAN implementation for generating Figures 2 through 4, setting the parameter samples number P=1000 (GMM).

Fig2-4 GAN高斯饱和loss与梯度20250713.ipynb: An analysis of Gaussian saturation loss and gradients in GANs, producing Figures 2 to 4 (samples number p=100, GMM).

Fig2ab 生成器loss和梯度.ipynb: A script dedicated to calculating and plotting the generator loss and gradients for Figure 2(a) and 2(b) (GMM).

Fig4 GAN 20260402.ipynb: A specific notebook containing the code to generate Figure 4 for the GAN experiments.(GMM)

Fig5-Mnist 2026.ipynb: Code for reproducing Figure 5 based on recent MNIST dataset experiments. (MNIST)

Fig7-8 CIFAR-GAN (2).ipynb: A secondary notebook used for generating Figures 7 and 8 to evaluate GAN performance on CIFAR.(CIFAR-10)

Fig7-8 CIFAR-GAN.ipynb: The primary script to generate Figures 7 and 8 exploring GAN results on the CIFAR dataset.(CIFAR-10)

Fig9 CIFAR10.ipynb: A notebook for plotting Figure 9, focusing specifically on CIFAR-10 experiments.(CIFAR-10)

FigCifar Fig9-2026.ipynb: An updated script for generating Figure 9 based on recent CIFAR dataset trials.(CIFAR-10)

FigMnist vsig sigma=1.0.ipynb: An experiment on the MNIST dataset analyzing visual signatures with the standard deviation (sigma) set to 1.0. (MNIST)

GAN高斯分布-Goodfellow loss训练.ipynb: A notebook training a GAN on a Gaussian distribution utilizing the original Goodfellow loss function.(GMM)

GAN高斯分布高斯GEU.ipynb: Implementation of a GAN learning a Gaussian distribution using a Generalized Exponential Unit (GEU).(GMM)
