## Improving On-Shelf Availability in Retail Stores using Machine Learning

### Albion Krasniqi

**Abstract**

This project identifies the problems of on-shelf availability (stock) monitoring in retail stores using traditional auditing methods. It further attempts to assess whether an automated approach can be used to increase the efficiency of stock monitoring. By using image recognition and supervised learning techniques, this method can detect products, count them in real-time, and finally update the shelf condition if replenishment is needed or not. The Densely Segmented Supermarket (D2S) is used as a dataset for training and testing. This dataset contains 21,000 high-resolution images of everyday products from 60 categories. Two object detection models were selected to be trained: Mask regional convolutional neural networks (R-CNN) and You Look Only Once (YoloV3) pre-trained model. After implementing and training these two models on D2S dataset, we conducted different experiments and achieved promising results. The Mask R-CNN model achieved an Mean Average Precision (mAP) of 73.8%, while the YoloV3 model reached an mAP of 46.1%.

Key Words: Machine learning, Deep Learning, Image Recognition, Stock Monitoring, On-Shelf Availability

**Work completed so far:** 

Both models were trained and implemented. Furthermore, I conducted few  experiments with each of them.  Check out the folders for more information. 

Below are the links the implementation notebooks: 

In each of the Github folders (model 1 & 2) listed above, there is a tutorial section, where I was able to successfully implement and train the Mask-RCNN and YOLO for the Kaggle fruit dataset. This dataset was much smaller compared to the main (D2S) dataset, it only had 300 images of 3 different classes.  

Link to D2S dataset: https://www.mvtec.com/company/research/datasets/mvtec-d2s

Link to Kaggle Fruit Dataset: https://www.kaggle.com/mbkinaci/fruit-images-for-object-detection


**Project structure**
```
├── README.md           <- The top-level README for developers using this project.

├── data
│   ├── raw             <- The raw data
│   ├── processed       <- The processed data
│
├── requirements.txt    <- Requirements for this project.
│
├── model_1_mask_RCNN   <- Models using R-CNN
├── model_2_YoloV3      <- YoloV3 model.
```
