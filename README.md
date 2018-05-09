# workshop
## installation
```
pip install tensorflow
# For GPU
pip install tensorflow-gpu
sudo pip install Cython
sudo pip install pillow
sudo pip install lxml
sudo pip install jupyter
sudo pip install matplotlib
```

## Set PYTHONPATH
```export PYTHONPATH=xxx/workshop:xxx/workshop/slim:$PYTHONPATH```

## Data and Model Required
Name | URL | Path
:------:|:---------------:|:---------------------:
data | [url](http://www.robots.ox.ac.uk/~vgg/data/pets/) | data/annotations; data/images
pre-trained model | [url](http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz) | models/faster_rcnn_inception_v2_coco_2018_01_28
well-trained mode | [url](https://pan.baidu.com/s/1qviS2WkeFNv6Bb_Ff0L--Q) | models/frozen_trained_inference_graph
