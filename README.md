# shooting-quantum-model
Include numerical solution for infinite well potentials and deep learning model to predict the same

The content includes , notebook files , data , and models prepared
note books can be run by cloning in to the repository , but care should be taken to change appropriate path inside the program to the users home directory, or the directory the repository is cloned into.

# infinite potential well 
Contains the shooting method algorithm which is used to solve the infinte potential well problem. Upto 4 eigen values are calculated and the corresponding wave functions are plotted. More eigen values can be found by adding little code as per the user requirments.Backward shooting can be done by rearrangng the starting and stopping point of the integration.

# Dataproduction 
The program produces csv files for the training.New data tables can be produced by appropriate changes in the potential function as required.

# Model training 
Keras using tensorflow backend is employed to create prediction models. The models are 3 layer dense and epochs are 200.Three example potential functions are used and only three parameters is used to avoid overfitting.

# Prediction model 
The notebooks predict the outcome of the test data using previously created models.

# Zero potential
The parameters and the example function were chosen such that setting all parameters to zero, implies Zero potential energy inside the well in all cases. so the output of this program allows us to compare the efficency of the model ,  and the results are not surprising

# Data
example data tables of train, validation and test data

# h5
models build using keras, import it using keras to run the model.

# Requirements
The calculations are cpu intensive , thus for the training processes it is recommended to use the GPU . If you have an NVIDIA GPU install CUDA and CUDNN along with the tensorflow-gpu module. Refer to the official websites for installation guides and more details.
