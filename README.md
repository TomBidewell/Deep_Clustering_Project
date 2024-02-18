# Deep_Clustering_Project

This notebook contains the code for my Bachelor's Thesis, researching different embedding techniques for clustering. In it I propose a new deep embedding based on AutoEncoders and Kullback Leibler (KL) divergence. Current state of the art methods create a probability distribution, Q, over the clusters using each point's distance to the centre of that cluster; an ideal distribution, P, is then made as a function of Q and the KL loss between the two is used to update parameters. The method I propose 
