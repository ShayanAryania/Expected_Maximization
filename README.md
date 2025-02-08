# Expected_Maximization
This EM algorithm implementation is designed to uncover hidden patterns in multiple DNA sequences, with a focus on identifying optimal motif locations and alignment positions. As an unsupervised learning technique, the EM algorithm is well-suited for discovering latent variables in complex data sets. The program's primary objectives are to provide a clear and efficient implementation of the EM algorithm and to facilitate the discovery of meaningful motifs and alignment positions in DNA sequences.

The motif locations and alignment positions are latent variables that require inference, as they are known to exist but cannot be directly observed. To address this challenge, the program employs a iterative approach, refining its estimates of these variables until convergence is achieved.

A key feature of this implementation is that the initial motif positions are randomly initialized, which means that each run of the program will produce unique results. However, the program's ability to consistently produce similar results when provided with the same input demonstrates its robustness.

The Expectation step is the algorithm's workhorse, responsible for calculating positional frequencies, odds ratios, and log-odds scores. These scores are then used to derive the log-likelihood function, which is optimized in the Maximization step. By iteratively refining its estimates of the motif positions and alignment scores, the program is able to identify the most likely motifs and alignment positions in the input DNA sequences.
