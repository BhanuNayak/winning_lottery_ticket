# winning_lottery_ticket
The problem statement "One ticket to win them all: generalizing lottery ticket initializations across datasets and optimizers" delves into the concept of lottery ticket initializations in neural networks.

It aims to investigate the transferability of initialization parameters derived from one dataset or optimizer to others, exploring the potential for streamlined training and optimization processes.

# Explaining about the python notebooks 
Training and Iterative_pruning.ipynb:
This file contains the code  necessary for iterative training on a source dataset and pruning on a target dataset to generate winning lottery tickets. This process is designed to model performance by iteratively refining its parameters based on the source and target datasets. The resulting weights can then be utilized to produce desired results, such as % of weights pruned and Accuracy on Pruned network.


Testing.ipynb:
This file  leverages weights generated during the iterative pruning phase to store all the results in a spreadsheet format. The file contains code that loads the pruned model with the optimized weights and performs testing or evaluation tasks using a test dataset. The results of these evaluations are then organized and stored in a spreadsheet for further analysis or reporting purposes.


Plotting:
Excel Files:
This folder contains the results generated in Testing phase
Notebooks:
These notebooks are used to plot graphs for better visual understanding.
