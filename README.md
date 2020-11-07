# Backdoor attacks repository:

It includes a list of Jupyter Notebooks produced to describe in a practical way, the conecction between math definition and algorithm, with the implemented code in `PyTorch`. In some of the cases, the original code released by the paper's author is reused and adapted and in other cases, a new code version is provided to illustrate the paper's main idea. 

## Selected list of publications:

1. **Universal adversarial perturbation** by Moosavi-Dezfooli et al.: This paper is considered as the core idea behind _Universal Litmus Patterns_. It suggest the existence of a vector v to be added to any image x able to misclassify the model's output in a high probability. A new implementation of the algorithm in `PyTorch` is suggested and included in the Jupyter Notebook, since the original version of the code released by authors is develoved in `Tensorflow`. 
[Notebook link](https://github.com/henrychacon/Backdoor_attacks/tree/main/Universal_adversarial_perturbation).

2. **Universal Litmus Patterns** by Kolouri et at.: Authors suggest a procedure to evaluate if a model was attacked during the training process (binary descriminiator). The classifier is constructed based on 400 clean models and 400 backdoors in terms of an unique universal test pattern. Which means, the ULP is indepedent from eather the training or testing set. [Notebook link](https://github.com/henrychacon/Backdoor_attacks/tree/main/Universal_litmus_patterns).

3. **Fingerprinting the Latent Space Distribution for Studying the Backdoor Attacks using D-vine copula auto-encoder (DCAE)**. In this Jupyter Notebook we present the evidence that backdoor attacks patterns are stamped in the memory of the model's parameters. Two main results are presented here. First one, triggers can be reproduced in the latent space of a model even if only clean samples are available. Second, backdoor attacks increase the entropy of the latent space. The used architecture is an auto-encoder (AE) for the MNIST data set and the D-vine copula method suggested to estimate the distribution in the reduced space. 
[Notebook link](https://github.com/henrychacon/Backdoor_attacks/tree/main/D-Vine_copula_auto_encoder).

4. **Axiomatic Attribution for Deep Networks** by Sundararajan et al.: In this paper, authors suggest the Integrated Gradients as a procedure to determine in the model the most relevant features from the input set. The suggested model does not require any change in the model. In the Notebook, the algorithm implementation for a CNN model is presented. [Notebook link](https://github.com/henrychacon/Backdoor_attacks/tree/main/Axiomatic_Attribution_Deep_Networks).

