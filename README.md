# TV Script Generation - *The Simpsons*

![The Simpsons](https://upload.wikimedia.org/wikipedia/en/0/0d/Simpsons_FamilyPicture.png)

This project trains a Recurrent Neural Network with LSTM (Long Short Term Memory) using TensorFlow on the text data of **_The Simpsons_** TV script, and generates, using the trained model, new TV script imitating the text in **_The Simpsons_** script.

The project is trained on AWS Ubuntu EC2 Instance with GPU. Training on CPU is not recommended.

Setting a working environment on AWS might be not difficult but pretty erroneous. I have written posts about [the possible problems while training the model](https://wszhan.github.io/2018/04/09/udacity-dlnd-p3.html) and on [how to set up Anaconda on AWS](https://wszhan.github.io/2018/04/09/installing-anaconda-on-ec2.html)(if you are using Anaconda version of TensorFlow-GPU). On [my blog](https://wszhan.github.io/) there are more posts on AWS and Neural Network.
