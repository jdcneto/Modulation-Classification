# Modulation Classification

This work make use of convolutional layer network on a synthetic dataset, generated with GNU Radio, consisting of 11 modulations (8 digital and 3 analog) at varying signal-to-noise ratios.
The file is formatted as a "pickle" file which was open using cPickle.load(...) 
Dataset Download: http://opendata.deepsig.io/datasets/2016.10/RML2016.10a.tar.bz2

The model was following https://arxiv.org/abs/1602.04105 and upgraded by pytorch.

References:

@article{convnetmodrec,
  title={Convolutional Radio Modulation Recognition Networks},
  author={O'Shea, Timothy J and Corgan, Johnathan and Clancy, T. Charles},
  journal={arXiv preprint arXiv:1602.04105},
  year={2016}
}

@article{rml_datasets,
  title={Radio Machine Learning Dataset Generation with GNU Radio},
  author={O'Shea, Timothy J and West, Nathan},
  journal={Proceedings of the 6th GNU Radio Conference},
  year={2016}
}
