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

## Data and Model required
data：http://www.robots.ox.ac.uk/~vgg/data/pets/
path：data/annotations; data/images

pre-trained model：http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz  
path: models/faster_rcnn_inception_v2_coco_2018_01_28

well-trained model：https://pan.baidu.com/s/1qviS2WkeFNv6Bb_Ff0L--Q 
path : models/frozen_trained_inference_graph
