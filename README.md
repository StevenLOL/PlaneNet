# PlaneNet

## Dependencies
Python 2.7, TensorFlow (>= 1.0), numpy, opencv 3.

## Getting started
To train the network from the pretrained DeepLab network, please first download the DeepLab model [here](https://github.com/DrSleep/tensorflow-deeplab-resnet) (under the Caffe to TensorFlow conversion), and then run the following command.

```bash
python train_planenet.py --restore=0
```
