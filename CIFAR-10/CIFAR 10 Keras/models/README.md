# These are the some pretrained model

## .h5py models are trained on  Google colaborotory (GPU accelerated Tensorflow 2.0)
## .h5 models are trained on my pc (Tensorflow 1.13)


###  use this code to simply load the model

'''

          from tensorflow.keras.models import load_model 

          new_model = load_model("models/cifar-10-keras.h5")

          new_model.summary()  # For model summary

'''
