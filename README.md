# L2-driving_system_CNN

The primary aim of this project is to "dip my feet" into the intersection of robotics and deep learning.<br>
----
A CNN is going to be applied to a training n-dimensional tensor of images of roadways and marked lanes, with labels corresponding to steering wheel angles at time step t of a given image. 
The goal is to "predict" or "output" the label (steering wheel angle) that has the highest probability distribution given the set of all angles at a given time step t, given an image. The model will then be deployed on a CARLA simulator to test its accuracy. 
The loss function would be based on minimizing the squared average distance between the model output and ground truth.
 Given enough time, I might want to deploy the model on a robot in a real-life setting. That would be fun.
