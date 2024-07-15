# Prediction of secondary structural regions of human UBE2C protein

# Part 2

This part includes Chou-Fasman algorithm.

# Part 3

Hidden Markov Model based predictor to predict secondary structural regions of proteins.

This part includes an HMM model with 4 states: helix, strand, turn and the unknown. First, the transition and emission probabilities are calculated based on given train data. Then the secondary structural elements of the human UBE2C protein sequence is predicted using Viterbi algorithm.


Notes: 
Transition rates of HMM is manually changed to get a better performance.
Pseudo-counts are not used in emission rates since none of the emission values are not zero.
