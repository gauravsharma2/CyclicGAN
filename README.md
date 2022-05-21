# CyclicGAN
# Simple, straight-forward implementation of CycleGAN in PyTorch

I have implemented this jupyter notebook while directly referring to some OLD papers.

The notebook, however, was not run for more than 10 epochs because I currently do not have access to a good GPU (still saving up for that!). Hope you have a better experience than me and I'm excited to see your results!

## Some changes to the original paper:

I added 2 discriminators for every generator. One of the discriminators works on 70x70 patches (as mentioned in the paper) and the other looks at the whole image. Later I aggregate the scores of both these discriminators for a better result. 

## TODO

Adding linear learning-rate decay if it is trained for more than 100 epochs.
