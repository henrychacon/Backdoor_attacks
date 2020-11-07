# Tracking Evidence of Backdoor Attacks in Latent Space Using Vine Copula Generative Model

The input space complexity determines the model's capabilities to extract their knowledge and translate the space of attributes into a function which is assumed in general, as a concatenation of non-linear functions between layers. In the presence of backdoor attacks, the space complexity changes, and induces similarities between classes that directly affect the model's training. As a consequence, the model tends to overfit the input set. In this research, we suggest the D-vine Copula Auto-Encoder (VCAE) as a tool to estimate the latent space distribution under the presence of backdoor triggers. Since no assumptions are made on the distribution estimation, like in Variational Autoencoders (VAE). It is possible to observe the backdoor stamp in non-attacked categories randomly generated. We exhibit the differences between a clean model (baseline) and the attacked one (backdoor) in a pairwise representation of the distribution. The idea is to illustrate the dependency structure change in the input space induced by backdoor features. Finally, we quantify the entropy's changes and the Kullback–Leibler divergence between models. In our results, we found the entropy in the latent space increases by around 27\% due to the backdoor trigger added to the input. 

The suggested methodology is depicted in the following figure:
![Figure](DvineCopula.png)

In the attached Jupyter Notebook, you can find the implemented code to run the following experiments:
