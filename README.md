# Object-Detection-RetinaNet--Eagleview

### Model name
Pytorch implementation of RetinaNet object detection as described in Focal Loss for Dense Object Detection by Tsung-Yi Lin, Priya Goyal, Ross Girshick, Kaiming He and Piotr Dollár.

This implementation is primarily designed to be easy to read and simple to modify.

### Links to dataset and framework
Dataset(trainval.tar.gz) - https://drive.google.com/file/d/1zKf-WcWbZgYkmFxQRDmEkLqiHlxSBenv/view?usp=sharing

Framework(Pytorch implementation of RetinaNet) - https://github.com/yhenon/pytorch-retinanet.git

### About the model
The retinanet model uses a resnet backbone. You can set the depth of the resnet model using the --depth argument. Depth must be one of 18, 34, 50, 101 or 152. Note that deeper models are more accurate but are slower and use more memory.

For this Notebook, I have used Resnet50 as Backbone.

### Inference
Currently, this Notebook achieves 24.0% mAP at 600px resolution with a Resnet-50 backbone.

Average Precision (AP) @[ IoU=0.50:0.95 | area= all | maxDets=100 ] = 0.240

Average Precision (AP) @[ IoU=0.50 | area= all | maxDets=100 ] = 0.540

Average Precision (AP) @[ IoU=0.75 | area= all | maxDets=100 ] = 0.176
