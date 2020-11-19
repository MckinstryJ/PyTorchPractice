# PyTorchPractice
General PyTorch practice. This will assist in the GPU enabled Neuro Dynamic Programming models used for the QuantDev project.

## Starter
An introduction to PyTorch which includes:
<ul>
  <li>How to do basic operations on tensors</li>
  <li>How to build a image classifer using a CovNet</li>
  <li>How to save / load a model</li>
  <li>How to train the same model on a GPU via CUDA</li>
</ul>

## Audio Classifier (TODO)
The audioclass.py file is an Audio Classifier based on the ESC-50 dataset. </br></br>
I followed the steps outlined here: [Audio Classification](https://medium.com/@hasithsura/audio-classification-d37a82d6715)</br></br>
However, the example is incomplete and his repo doesn't provide anything similar to what he mentioned in the article. This will have to be revisited to add the missing parts and provide similar results that are in his actual code. I have already made some improvements to his base code so I'll probably come back to this to continue my approach.

## Mel Spectrogram (TODO)
The melspectro.py file is a simple example of how to build a Mel Spectrogram via some audio file. The Mel values could be used to generate a average value between bins and then with each new audio a correlation could be build to match it with a known example. Which would give the user a list of what the sound is based on a defined threshold.

## Tensorboard (TODO)
Major feature of PyTorch is being able to visualize the model and its progress in its training / testing. The file tensorboard.py shows a basic example of how to do that using the Fashion MNIST dataset. The code only shows a 4 image grid but I'll come back to this to develop it further.

## Deep Q Network
In the DQN.py file, I demostrate how one can build a Deep Q Network with PyTorch. A DQN is a reinforcement learning model that uses a neural network to approximate rewards for each action in a given state. In my OpenAI_RL project, the DQN does far better than most RL models but this example uses PyTorch instead of Keras.
