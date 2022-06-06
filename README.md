# Ship-Measurement-Prediction-with-CNN-master

## Short Description
- In vessel, there are various parts such as D/HOUSE, H/COVER, Inside E/RM, Inside C/HOLD, Inside WBTK, T/SIDE, S/BTM, F/BTM, Inside Peak TK according to countries where the ship was made, what kind of stuff are you carrying, and what engine the ship uses such as Steam Turbine Engine, MAN Electronic Gas-Injection, Magneto-Hydro Dynamics, etc (we call this parameters).
- The goal of this project is to predict the measurement values of each area of the ship according to which engine is used and what goods are being carried in order to reduce the ship design cost when building a new ship.


## DataSet
- The Dataset is confidential by company.
- The characteristic of data is that the number of data in the output node is larger than the number of data in the input node. In other words, there are many measurement values that need to be predicted compared to the parameter values.
- In vessels, there are A ~ F types, each type of vessel has 6, 23, 5, 5, 15, 16 input nodes for training data (parameters) respectively, while 47 output nodes.


### Training Concept
- One of output nodes is trained by all of input nodes, so each output node has each model.
