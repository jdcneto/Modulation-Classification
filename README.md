# Modulation Classification

This work make uses of convolutional neural networks on a synthetic dataset, generated with GNU Radio, consisting of 11 modulations (8 digital and 3 analog) at varying signal-to-noise ratios.
The file is formatted as a "pickle" file which was open using cPickle.load(...).
Dataset website: http://opendata.deepsig.io/datasets/2016.10/RML2016.10a.tar.bz2

The model was following https://arxiv.org/abs/1602.04105 and upgraded to pytorch.
