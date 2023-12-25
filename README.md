


# Spatiotemporal Analysis and Prediction of Global Societal Unrest
### Group 20: Anol Kurian Vadakkeparampil - 56268544 ,  Aadithya Kandeth - 69802791

## Code Structure Breakdown:

**ATDS_Base:** contains all traditional models trained on the gdelt dataset.
These models include:
1. Basic Deep Neural Network
2. Random Forests
3. K Nearest Neighbors
4. Hidden Markov Models
5. TabNET
6. XGBoost
Also includes graph visualization using networkX

**ATDS_GNN:** Contains the graph neural network implementation of the code.

**ATDS_LMM:** Contains implementation of the LLM being used for predicting social unrest (OpenAI)

**Data Folder**: Contains all csv files required for running the code. 


## Execution Steps:
1. Open the notebook of your choice.
2. Run all cells


### Notes:
1. API Keys have to be added for running the ATDS_LMM notebook. The requirement has been highlighted as a comment in the code
2. We have provided only one month of GDELT data for running purposes. The overall GDELT data size of 250GB+ is too large to be shared. Note that this does not reflect the whole dataset and could be highly biased/ class imbalanced since there is only one month. Model predictions will also reflect the same.
