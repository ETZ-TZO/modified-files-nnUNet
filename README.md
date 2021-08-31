# Changes that were made to nnUNet as described in 

These changes allow for training on different sets of labels at once. 
In the paper, we train on the contrast enhanced tumor for meningioma.
We further train on the whole tumor, contrast enhanced tumor and tumor core for examples from the BraTS2020 dataset.
All changes are indicated by a comment stating 'Sander edit'.

The code is dependend on the names of our datafiles (niftis) to distinguish between BraTS data and our own data. 
