# Classify burning liquids using a static flame image

Developed a convolutional neural network to identify the burning liquid using static flame images. Fine-tuned a pretrained ResNet-34 model. Began by freezing all layers except the fully connected classifier layer(s). Trained the model with a small learning rate over several epochs. Then progressively started unfreezing layers to adapt the pretrained model to the new dataset.

Burning liquid dataset taken from https://doi.org/10.1007/s10973-021-10903-2
