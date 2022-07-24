# GMML

GMML pretext based techniques for training computer vision models in a self-supervised manner. GMML are tranformation applied to the input image that include injecting to image , replacing parts of the image with other images in the batch. Once the transformation are applied the image injected to the model(Transformer network) which the reconstrcted version of the origanl image. L1 loss is computed between model output and orginal image(without transformations). The objective of training the model in such is a way is to allow the network to learn the rich sematics of the image which the are prevented when model is traiend in supervisied way. This work is implementation of GMML IS ALL YOU NEED paper which is currently the State-of-the-art techniques for traning computer vision model in self-supervised way.

PAPER: https://arxiv.org/abs/2205.14986#:~:text=Vision%20transformers%20have%20generated%20significant,known%20to%20be%20data%20hungry.

