# hip-cat

Model corresponding to preprint “A neural network model of hippocampal contributions to category learning” (Sucevic & Schapiro, 2022)

This repository contains a neural network model, based closely on Schapiro et. al. 2017, Philosophical Transactions of the Royal Society B, which we used to explore hippocampal contributions to category learning. We simulated three category learning paradigms. For each paradigm, there are two networks, one simulating intact hippocampal learning and another simulating category learning with lesioned hippocampal pathways.

### In Control Panel:

1. Select a network
2. Select training (‘train_patterns’) and test set (‘test_patterns’)
3. Specify the number of epochs (‘num_trials_per_epoch’)
4. Specify the number of epochs per batch
5. Specify the number of batches
6. To simulate MSP lesion, set parameter MSP, representing a projection from ECin to CA1, to 0 (default value is 3). To simulate TSP lesion, set parameter TSP, which represents projections from CA3 to CA1, to 0 (default value is 1).
