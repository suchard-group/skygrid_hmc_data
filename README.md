# skygrid_hmc_data
BEAST XML files accompanying the manuscript 'Hamiltonian Monte Carlo sampling to estimate past population dynamics using the skygrid coalescent model in a Bayesian phylogenetics framework' by Guy Baele, Mandev S. Gill, Philippe Lemey, and Marc A. Suchard

The data sets analysed are the following:
* Ebola data set from [Dudas et al., 2017](https://doi.org/10.1038/nature22040), subset by [Hill and Baele, 2019](https://doi.org/10.1093/molbev/msz172)
* Rabies data set from [Biek et al., 2007](https://doi.org/10.1073/pnas.0700741104)
* Rice yellow mottle virus (RYMV) data set from [Trovao et al., 2015](https://doi.org/10.1093/molbev/msv185)

Files marked *fixed* assume a provided or user-defined tree topology, whereas files marked *variable* estimate the tree topology during the analysis.
Files marked *BUMCMC* employ a block-update Markov chain Monte Carlo transition kernel [Gill et al., 2013](https://doi.org/10.1093/molbev/mss265), whereas files marked *HMC* employ the Hamiltonian Monte Carlo transition kernel discussed in our manuscript.
