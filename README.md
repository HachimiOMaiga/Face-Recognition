# Face-Recognition
### Implement the triplet loss function
* Use a pretrained model to map face images into 128-dimensional encodings
* Use these encodings to perform face verification and face recognition

Used a pre-trained model which represents ConvNet activations using a \"channels first\" convention, as opposed to the \"channels last\"
convention i.e. a batch of images will be of shape (m, n_C, n_H, n_W) instead of (m, n_H, n_W, n_C)
