#
The Nature Conservancy Fisheries Monitoring
This is the kaggle competition https://www.kaggle.com/c/the-nature-conservancy-fisheries-monitoring

### Part 0 : Collecting data

Download data from this url https://www.kaggle.com/c/the-nature-conservancy-fisheries-monitoring/data
extract the data to folder name fishes

### Part 1 : label the box for object
using label_pointer.py script to label the box of object or using the annotation


### Part 2 : Faster R-CNN

Train faster RCNN t

### Files description

1.  `label_pointer.py` : point with mouse clicks to save bounding box coordinates on annotations text file (from already labeled pictures)
2.  `train_frcnn.py -p annotation.txt` : training Faster R-CNN with data from the annotation text file
3.  `test_frcnn.py -p path/test_data/` : testing Faster R-CNN

![Result picture](https://github.com/alexattia/SimpsonRecognition/blob/master/pics/bao_ve_ca_map.png)
