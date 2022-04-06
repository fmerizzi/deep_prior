# deep_prior
some general notes and approaces on deep image prior

## paper notes
1) the structure of a generator network is sufficient to  capture imae statistics 
2) INVERSE PROBLEMS, randomly initialized network can be used as prior
3) THE STRUCTURE OF THE NETWORK MUST RESONATE WITH THE STRUCTURE OF THE DATA
4) you need a generator network 
-------------
1) I start with some random weights to the NN and iteratively update THEM 
2) updating with a comparison to the original image, super resolution is reasonable 
3) a network untrained descends much faster towards a "real" image rather than random noise.
4) in inpainting, I'm just calculating the loss on the non-mask pixels! sounds pretty reasonable!
5) 



## future developments 
- taking into consideration the likeness of a network to rebiuld random vs non random images. 
maybe related to a so called random distance.. 
- what if we sample the random creations a CNN and use them instead of random layers? huh?
- 
