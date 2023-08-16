# Autopilot-TensorFlow
A TensorFlow implementation of this [Nvidia paper](https://arxiv.org/pdf/1604.07316.pdf) with some changes.
<img src="https://i0.wp.com/softwareengineeringdaily.com/wp-content/uploads/2018/10/self-driving-car-02.png?fit=1190%2C595&ssl=1">

# How to Use


Use `python train.py` to train the model

Use `python run.py` to run the model on a live webcam feed

Use `python run_dataset.py` to run the model on the dataset

To visualize training using Tensorboard use `tensorboard --logdir=./logs`, then open http://0.0.0.0:6006/ into your web browser.

### Demo 
<img src="demo.gif">

- Credits: https://github.com/SullyChen/Autopilot-TensorFlow
- Research paper: End to End Learning for Self-Driving Cars by Nvidia. [https://arxiv.org/pdf/1604.07316.pdf]

- NVidia dataset: 72 hrs of video => 72*60*60*30 = 7,776,000 images
- Nvidia blog: https://devblogs.nvidia.com/deep-learning-self-driving-cars/






