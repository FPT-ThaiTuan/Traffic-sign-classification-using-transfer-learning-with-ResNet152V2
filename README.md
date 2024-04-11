# **Traffic sign classification using transfer learning with ResNet152V2**

## **1. Introduction**
- In today's rapidly evolving world, the integration of artificial intelligence (AI) and computer vision technologies into various sectors has become increasingly prevalent. One critical application area is traffic sign classification, which plays a pivotal role in enhancing road safety and facilitating autonomous driving systems. In this context, the adoption of advanced deep learning architectures, such as ResNet152V2, has demonstrated remarkable effectiveness in achieving high accuracy and robustness in traffic sign recognition tasks. This paper explores the utilization of ResNet152V2 for traffic sign classification, aiming to provide insights into its performance and potential applications in real-world scenarios.

## **2. Abstract**
- This study investigates the utilization of ResNet152V2, a state-of-the-art deep learning architecture, for traffic sign classification tasks. Leveraging a comprehensive dataset comprising 52 different types of traffic signs, the proposed approach aims to achieve high accuracy and precision in identifying various sign categories. Through extensive experimentation and evaluation, our results demonstrate the effectiveness of ResNet152V2 in accurately recognizing traffic signs, with a precision rate of 99%. The findings highlight the potential of leveraging advanced deep learning models for enhancing road safety and enabling robust autonomous driving systems in real-world environments.

## **3. ResNet152V2**
- ResNet152V2 is a deep neural network architecture developed by the team at Microsoft Research. It is a variant of ResNet (Residual Network), a very powerful and popular type of deep neural network in the field of computer vision.
- The configuration structure of ResNet152V2 consists of several main blocks, called residual blocks, and several convolutional, pooling, and fully connected layers. The special feature of ResNet is to use skip connections (skip connections) to avoid the phenomenon of gradient disappearance and help the network learn deeper symbols. ResNet152V2 is built on top of ResNet with a remaining block count of 152, which increases the depth of the network and improves its representation learning ability.
- The ResNet152V2 network also uses techniques such as batch normalization and rectified linear units (ReLU) to speed up the training process and reduce overfitting. Additionally, it applies techniques such as bottleneck blocks to reduce computational complexity while maintaining high performance.
- You can see the structure of ResNet152V2 below [1]

![屏幕截图 2024-04-11 214112](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/d5d9b06e-e218-473b-a62c-c2e0ec8d092d)

## **4. Project**
### **4.1. Data visualization**
- Displays the number of each traffic sign

![屏幕截图 2024-04-11 220637](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/27881bb9-63d0-4aed-8ddd-089836c95714)

- Displays a photo of each traffic sign

![屏幕截图 2024-04-11 220817](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/9c150306-bbf1-4c12-be07-d97f33ea1043)

### **4.2. Data augmentation**
- TensorFlow's image generator is a powerful tool in generating input data for machine learning models, especially in image processing. In the code you provided, we are using ImageDataGenerator to generate variations of the training images so that our model learns to diversify and augment the data.
### **4.3. Load the pre-trained model and edit**
- Download the pre-trained model
- Edit desired output according to project. Here are 52 traffic signs

![屏幕截图 2024-04-11 221948](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/2ebf44f4-df12-408d-80de-dd62183c6089)

### **4.4. Build models**
- Model training process

![屏幕截图 2024-04-11 222120](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/0c93c8b7-9f3d-4d34-ace9-4feb9f660ac8)

### **4.5. Result**
- Plot the loss of training and validation

![屏幕截图 2024-04-11 222217](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/7f00c1c8-a203-43eb-9188-26bcb4653863)

- Plot the accuracy of training and validation

![屏幕截图 2024-04-11 222312](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/5f286b8c-988b-4d93-b6f6-2f13f99c58e1)

### **4.6. Test the model with real data**
- Results with test data set

![屏幕截图 2024-04-11 222426](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/7c7f4547-9cbd-4a9e-b264-de1e082d32b4)

## **5. References**
[1] Multi-classification deep learning models for detection of ulcerative colitis, polyps, and dyed-lifted polyps using wireless capsule endoscopy images. [Here](https://link.springer.com/article/10.1007/s40747-023-01271-5)


### **Hope this article can help you.**

### **If you have any questions please contact me for help!**

### **Gmail: tuanddt.ai.work@gmail.com**

### **Kaggle: [Tuan_AI](https://www.kaggle.com/tuanai)**

### ***Thanks everyone!***
