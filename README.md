# Novelty-Facilitated Synaptic Plasticity

## Overview

Python implementation of [Dynamics of memory representations in networks with novelty-facilitated synaptic plasticity](https://www.sciencedirect.com/science/article/pii/S0896627306006386)

The model consists in an extended Hopfield Network with a Novelty Signal to store in and retrieve from memory morphed patterns.

## Requirements

- [Python](https://anaconda.org/anaconda/python)
- [Jupyter](http://jupyter.org/)

## Denoising task

### Morph sequence: p=5 patterns (on 16 neurons)

- Noisy stimuli

![Noisy_Stimuli4](./gitimg/Noisy_Stimuli4.png)

- Standard Hopfield Net Recall
![Hopfield_Recall4](./gitimg/Hopfield_Recall4.png)

- Extended Hopfield Net Recall
![Novelty0_biased_Recall4](./gitimg/Novelty0_biased_Recall4.png)


### Morph sequence: p=9 patterns (on 32 neurons)

- Noisy stimuli

![Noisy_Stimuli8](./gitimg/Noisy_Stimuli8.png)

- Standard Hopfield Net Recall
![Hopfield_Recall8](./gitimg/Hopfield_Recall8.png)

- Extended Hopfield Net Recall
![Novelty0_biased_Recall8](./gitimg/Novelty0_biased_Recall8.png)


### Morph sequence: p=33 patterns (on 128 neurons)

- Extended Hopfield Net Bassins of Attraction (gradual learning protocol)
![Novelty0_biased_PCA32](./gitimg/Novelty0_biased_PCA32.png)

- Extended Hopfield Net Bassins of Attraction (mixed learning protocol)
![Novelty1_biased_PCA32](./gitimg/Novelty1_biased_PCA32.png)



## Acknowledgments

Special thanks to [Pr. Jean-Pierre Nadal](http://www.lps.ens.fr/~nadal/) (École Normale Supérieure) for his course on Computational Neuroscience at ENS Cachan (M2 MVA).

## Author

Michel Deudon / [@mdeudon](https://github.com/MichelDeudon)
