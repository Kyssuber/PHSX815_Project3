# PHSX815_Project3

DiceRollFaceThree.py [-seed number] [-p3 fraction] [-Nroll number] [-Nexp number] [-output filename] 

---> generates dice rolls with face-three probability p3, Nexp experiments, and Nroll trials per experiment.

DiceAnalysis.py [-input filename] [-p3 fraction]

---> output includes posterior distribution plot for Npass3/Ntot probabilities per experiment; LLR vs. p_hat plot with best-fit curve via scipy.optimize.curve_fit, which is then used to print uncertainties associated with the maximum likelihood probability (LLR=0). 
