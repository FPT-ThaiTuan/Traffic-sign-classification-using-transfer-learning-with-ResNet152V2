# **Traffic sign classification using transfer learning with ResNet152V2**

## **1. Introduction**
- In today's rapidly evolving world, the integration of artificial intelligence (AI) and computer vision technologies into various sectors has become increasingly prevalent. One critical application area is traffic sign classification, which plays a pivotal role in enhancing road safety and facilitating autonomous driving systems. In this context, the adoption of advanced deep learning architectures, such as ResNet152V2, has demonstrated remarkable effectiveness in achieving high accuracy and robustness in traffic sign recognition tasks. This paper explores the utilization of ResNet152V2 for traffic sign classification, aiming to provide insights into its performance and potential applications in real-world scenarios.

## **2. Abstract**
- This study investigates the utilization of ResNet152V2, a state-of-the-art deep learning architecture, for traffic sign classification tasks. Leveraging a comprehensive dataset comprising 52 different types of traffic signs, the proposed approach aims to achieve high accuracy and precision in identifying various sign categories. Through extensive experimentation and evaluation, our results demonstrate the effectiveness of ResNet152V2 in accurately recognizing traffic signs, with a precision rate of 99%. The findings highlight the potential of leveraging advanced deep learning models for enhancing road safety and enabling robust autonomous driving systems in real-world environments.

## **3. ResNet152V2**
- ResNet152V2 is a deep neural network architecture developed by the team at Microsoft Research. It is a variant of ResNet (Residual Network), a very powerful and popular type of deep neural network in the field of computer vision.
- The configuration structure of ResNet152V2 consists of several main blocks, called residual blocks, and several convolutional, pooling, and fully connected layers. The special feature of ResNet is to use skip connections (skip connections) to avoid the phenomenon of gradient disappearance and help the network learn deeper symbols. ResNet152V2 is built on top of ResNet with a remaining block count of 152, which increases the depth of the network and improves its representation learning ability.
- The ResNet152V2 network also uses techniques such as batch normalization and rectified linear units (ReLU) to speed up the training process and reduce overfitting. Additionally, it applies techniques such as bottleneck blocks to reduce computational complexity while maintaining high performance.
- You can see the structure of ResNet152V2 below

![屏幕截图 2024-04-11 214112](https://github.com/FPT-ThaiTuan/Traffic-sign-classification-using-transfer-learning-with-ResNet152V2/assets/105273233/d5d9b06e-e218-473b-a62c-c2e0ec8d092d)

[Image source](https://link.springer.com/article/10.1007/s40747-023-01271-5)

## **4. Project**
### **4.1. Data visualization**
