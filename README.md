## Simulate Self Driving Car
This project will take you through how to simulate self driving car 

### Dependencies
You can install all dependencies by running one of the following commands

You need a anaconda to use the environment setting.

```
# Use TensorFlow without GPU
conda env create -f environments.yml 

# For to activate conda env use cmd follows:
source activate Self-Driving-Car

```
You can also install it from 

### Run the pretrained model
Start up the [Udacity self-driving simulator](https://github.com/udacity/self-driving-car-sim), choose a scene and press the Autonomous Mode button. Then, run the model as follows:

```
python drive.py model.h5

```

### To train the model
You'll need the data folder which contains the training images.

```
python model.py

```
model file look like model-<epoch>.h5

### To test the model

Replace the model file you wanted to use  in following File:

```
python drive.py

```

### Inspiration

Idea to use simulator,to simplify learning :[Siraj Ravel](https://github.com/llSourcell)