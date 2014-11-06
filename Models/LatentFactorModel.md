#Latent Factor Model


Given a rating matrix R which contains x users and i movies and also the unknown ratings. r(x,i) rating of movie i by user x.

We'll define two matrixs P and Q using SVD(singular vector decomposition) such that:

minimize(P,Q) with Summition over ((i,x) belongs to R(only rated values)) for (r(x,i) , q(i) * p(x)T)^2



