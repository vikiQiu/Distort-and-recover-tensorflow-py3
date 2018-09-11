# Distort-and-recover-tensorflow-py3
Code for "Distort-and-Recover: Color Enhancement with Deep Reinforcement Learning", CVPR18

## Overview
A version for python3 and tensorflow 1.10.0

The origin [code](https://github.com/Jongchan/DISTORT-AND-RECOVER-CVPR18) from the writer **Jongchan**.

- Get `vgg.pyz` from [VGG in Tensorflow](https://www.cs.toronto.edu/~frossard/post/vgg16/).
- Before training,prepare MIT5K train/test images in separate folders (train/raw/, train/target/, test/raw/, test/target/). And edit the path in main.py accordingly.

### Run the model

**Train the model:**

`CUDA_VISIBLE_DEVICES=3 python3 main.py --prefix test_run --gpu='3'`
