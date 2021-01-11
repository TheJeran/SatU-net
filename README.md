# SatU-net

![banner](https://i.imgur.com/eAbXQQG.png "Example")

## How to Use
* Download the files to a seperate folder on your machine. Unzip the fields model. Download and unzip the [classifier](https://drive.google.com/file/d/1Ws9Ync7Tragwy_Yc-jnGucnebWJq5gTd/view?usp=sharing) if you are not training your own.

* Follow the instructions in the respective notebooks
* 10 sample images are provided to test the code and model predictions

## Update
Implemented a vectorized one-hot maker into the training itself. This negates the need to save one-hot files to disk.
This method reads files at 1/3rd the speed as loading the array from disk. However, this should speed up with lower resolution images

