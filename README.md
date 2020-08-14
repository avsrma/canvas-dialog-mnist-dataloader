# Canvas Dialog MNIST Dataset
MNIST Digits with attributes like digit color, background color and style are placed at random positions on a 128x128 canvas. The digits are allowed overlap upto 40% and are randomly resized between 15 to 28. Aspect ratio is not maintained. Below is an example of an image provided by the dataloader. 

![](resized.png)

The dataloader class provides images, labels, bounding boxes, digit-color, background color, and digit-style. 

# Introduction 
This repository presents Canvas Dialog MNIST dataset. The code is based on Python and PyTorch. The dataset is inspired by [MNIST Dialog Dataset][1] and [MNIST Guess Number Dataset][2]. 

[1]: http://cvlab.postech.ac.kr/research/attmem/
[2]: https://github.com/ruizhaogit/MNIST-GuessNumber
