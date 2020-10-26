# Object Detection in Video in JavaScript

The idea of my project is to implement object detection,
using TensorFlow-JS and based on a video stream.
The object detection is performed in real-time on the browser,
augmenting the video stream with bounding boxes & classification.

For the model I plan to use YOLOv4 (or another state-of-the-art
network) for Object Detection, potentially coupled with an efficient
backend network like  MobileNet V2.

I plan to use TensorFlow for the implementation, which will allow to
"easily" switch to TensorFlow.js for the inference later.

Learning will be performed in Python, using TensorFlow,
with data from MS-COCO.
Transfer learning shall be applied to freeze the layers of
the detection backend with pre-trained weights from Imagenet.

## Dataset to be used

For training I intend to use the COCO dataset.

For evaluation downloadable videos will be used.

## Work-Breakdown Structure

The following tasks are planned for this project:

1. Data collection - 2 days
2. Network design - 3 days
3. Training and fine-tuning - 10 days
4. Building an application - 10 days
5. Writing of the report - 3 days
6. Preparing presentation - 1 day

While I have some compute capacity available for the training,
I assume some longer training time needed - therfore the estimate
of two weeks to have the training and fine-tuning completed.

Building the application will include converting the model into 
a TensorFlow.js model and building an application for performing
realtime inference from video frames - both things I'm not experienced
with but hope to be able to solve within some reasonable timeframe
thanks to Google...

## Topic

The project fits into the topic "Detection of Object".

## Project Type

The project fits into the project type "Bring your own method".

## Relevant Literature

[Microsoft COCO: Common Objects in Context](https://arxiv.org/pdf/1405.0312.pdf)

[YOLOv3: An Incremental Improvement](https://arxiv.org/pdf/1804.02767.pdf)

[YOLOv4: Optimal Speed and Accuracy of Object Detection](https://arxiv.org/pdf/2004.10934.pdf)

[MobileNets: Efficient Convolutional Neural Networks for Mobile VisionApplications](https://arxiv.org/pdf/1704.04861.pdf)

[Searching for MobileNet V3](https://arxiv.org/pdf/1905.02244.pdf)
