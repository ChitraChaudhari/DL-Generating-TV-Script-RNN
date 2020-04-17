# Generating TV Script

## Introduction

This repository contains the project, where you can generate your own Seinfeld TV scripts using RNNs. I used a Seinfeld dataset of scripts from 9 seasons. The Neural Network build will generate a new, "fake" TV script. 

## Steps involved

- Creating Lookup table
- Batching the data
- Building the Network
- Setting hyperparameters
- Training the model
- Generating Text

## Here's the sample output generated 

```
jerry: if its their annual terrorist luncheon.
joel:...
helen: you know, you cant be so particular. nobodys perfect.
jerry: i know, im sorry...
jerry: i have other stuff. y- you should come see me on, are the people call the police. 
       so now i have a decision do i walk or do i eat?
jerry: hm. you ate.
george: we sat there for twenty minutes, chewing, staring at each other in a defunct relationship.
jerry: someone says, go, uh, let me get this spatula... and im not gonna do it.
jerry:(laughing) really? what a shock.
helen: goodbye, jerry.
jerry: take care.
helen: well call you.
morty: bye, jer.
jerry: bye, dad. take it easy.
morty: bye, mr. kramer.
kramer: yeah. so long, morty.
jerry: so, when do i get my dinner?
kramer: theres no dinner. the bets off. im not gonna do it.
jerry:(laughing) really? what a shock.
helen: goodbye, jerry.
jerry: take care.
```

## Project Instructions

### Instructions

- Clone the repository 
 
- Make sure you have already installed the necessary Python packages 
    
    Dependencies
    - Python
    - PyTorch
    - Numpy

- Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

	jupyter notebook dlnd_tv_script_generation.ipynb
  
NOTE: In the notebook, you will need to train RNN in PyTorch. If your RNN is taking too long to train, feel free to pursue one of the options under the section Accelerating the Training Process below.

### (Optionally) Accelerating the Training Process

If your code is taking too long to run, you will need to either reduce the complexity of your chosen RNN architecture or switch to running your code on a GPU. You can use Amazon Web Services to launch an EC2 GPU instance. (This costs money) or You can try using colab provided by google.
