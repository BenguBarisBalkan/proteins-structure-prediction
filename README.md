# BBM411/AIN411: Fundamentals of (Introduction to) Bioinformatics
# Assignment 2 - Part 3

Hidden Markov Model based predictor to predict secondary structural regions of proteins.

This project includes an HMM model with 4 states: helix, strand, turn and the unknown. First it calculates the transition and emission probabilities based on given train data. Then predicts the secondary structural elements of the human UBE2C protein sequence.


Notes: 
Transition rates is manually changed to get a better performance.
Pseudo-counts are not used in emission rates since none of the emission values are not zero.