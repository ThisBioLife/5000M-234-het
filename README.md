5000M-234-het Control Files
======================

Here are the control files for the 5000M[234]-het datasets for reproduction purposes.

## Dataset Generation

Each replicate (`R0`, `R1`, etc.) contains a `longindel` folder, in which the `control.txt` file for INDELible is present. The control file references the two other `txt` files as indel length distribution.

## Other Notes

The model trees in the control files were taken from previous runs of INDELible where INDELible was instructed to generate non-ultrametric trees based on topologies generated from random birth-death trees. That is why the trees already have branch lengths attached.