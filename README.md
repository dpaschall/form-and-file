# form-and-file
The Form and File Project - Let Machines do the sorting for you!

Current state of affairs:

imported the tutorials from tensorflow.org
https://github.com/tensorflow/models
  Projects/tensortutorials/models/tutorials/

Tested out this new model for image recognition!
Described here: https://www.tensorflow.org/tutorials/image_recognition
it works.

Now we need to see what happend to our Cifar10 Model. Its currently training...
{ SUPER USEFUL INFO FOR OUR SERVER: http://askubuntu.com/questions/8653/how-to-keep-processes-running-after-ending-ssh-session }
The training is under: tmux list-sessions
named: cifar10training
You'll need to login to the ssh like normal then use the tmux command to see how our model is doing...or it is done. If it worked, then we can go to the next step of creating our model for form-and-file--->

Next step:
https://www.tensorflow.org/tutorials/image_retraining
create this directory for our inception model Projects/form-and-file/models/inception/
create this directory for our image database Projects/form-and-file/imgs/
create this directory for our image processing scripts Projects/form-and-file/generate/
...and any other directories you need...

TASK LIST:
DONE: Confirm the Cifar10 Model worked
Go about modifying the inception model's last layer for the form and file sorter
  Projects/form-and-file/
  
  
  Final Objective
From Picture(pixel-size-constant) to sorted, searchable pdf(or word) file names and tags. Machine learned algorithm that takes    (distorted or human written) forms it knows and automatically categorizes them using CNN (no not the news channel, a convolutional neural network).
  
  
  
