# AFN
a pytorch implement of Adversarially Adaptive Normalization for Single Domain Generalization
a official implement of **AFN: Adaptive Fusion Normalization via Encoder-Decoder Framework** [https://arxiv.org/abs/2308.03321]

AFN improve about 0.1%, so change the BN can make a difference!!

As for only 0.1%, I think that's because there are 6 domain both in training set and test set. If there are only 1 domain in test set, it can improve more.

So, this proves that, ASRNorm can improve at least 0.1% because it can discriminate difference domain by dynamic parameters.
