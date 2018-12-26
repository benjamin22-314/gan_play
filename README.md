### Basic Generative Adversarial Networks 

Ben Phillips
[Personal Website](https://benjaminphillips22.github.io)

Here I create a Generator function that can generate points from a 2D distribution. In this case, that distribution is a sine wave. To train the Generator, a Discrimitor is also used, which is trained to discern the difference between data from the real distribution and the generatored distribution. This medium [article](https://medium.com/@devnag/generative-adversarial-networks-gans-in-50-lines-of-code-pytorch-e81b79659e3f) by Dev Nag was extremely helpful in understanding and implementing this prject

View `gan.py` for the code used the create the gif below. If it takes too long to run on your computer, you can run it on google colab.

Description of first gif

![alt text](gan_f_0.gif)

Description of second gif

![alt text](gan_f_1800.gif)

Description of third gif

![alt text](gan_f_4500.gif)