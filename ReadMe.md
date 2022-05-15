### Assumptions:
#### The images are similar to the one's on which the model was trained earlier so I used a pre-trained model(YOLOV5) and fine tuned it on the given dataset.

### Model Name: 
#### YoloV5 -> Yolov5 is a PyTorch implementation. This model is an improvement on the previous versions of Yolo. 
#### YOLO v5 is extremely fast and lightweight and performs better than YOLOV3 and YOLOV4 in terms of accuracy.
#### Reference Links Used: https://pytorch.org/hub/ultralytics_yolov5/

### Dataset Creation:
#### The dataset had annotations stored in a json-file. So I used the json-file to create the Yolov5 labels.
#### Converted the COCO labels to YOLOV5 labels.

### Training and Metrics:
#### I used Yolov5 small model for training.The training was done on the GPU(colab) for 150 epochs, batch_size = 16
### Inference: Confidence: 0.1
#### mAP : 0.88
### Speed: 0.3ms pre-process, 14.3ms inference

### Conclusion and Recommendations:
#### The model is performing decently on the test set. The model performace can be improved further by: 
#### 1. Add more data for training and fine tune the model.
#### 2. Use different model.
