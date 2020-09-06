# Semantic-Segmentation-of-Urban-Scene-Images-Using-Recurrent-Neural-Networks
The Autonomous driving vehicles receive pixel-wise sensor data from RBG cameras, point-wise depth information from LIDAR (Light Detection and Ranging) sensors, and RADAR measurements (Radio Detection and Ranging) sensors. The desired output is just the steering angle, torque, and brake. The autonomous vehicle's computer has to understand the scene entirely, to make an accurate decision. So, understanding each pixel of the driving scene image will contribute to the vehicle's decisions.
Semantic Segmentation is the task of assigning a class label (Such as Car, Road, Pedestrian, or Sky) to each pixel in the given image. Knowing the object's exact shape is crucial for autonomous driving vehicles to make decisions, Such as turning the car to avoid obstacles. So, a better performing Semantic Segmentation Algorithm will contribute to the Autonomous Driving Vehicles field advancements.

Traditional methods to solve Semantic Segmentation are mainly based on handcrafted features and feature extraction methods. Since the rise of deep learning, almost everyone is using deep learning to deal with Semantic Segmentation. Convolutional Neural Networks (CNNs) achieved state-of-the-art performance on many Computer Vision tasks, including Semantic Segmentation. The most common problem faced by the current state-of-the-art networks is the inability to efficiently segment the edges and boundaries. Some works made use of Recurrent Neural Networks (RNNs) to deal with Semantic Segmentation. But there are many architectures left to investigate their performance effect in dealing with Semantic Segmentation. Our study addresses this Research gap.


Our work's main idea is "To use RNNs as an add-on module, to augment skip connections in Semantic Segmentation Networks through residual connections". In our work, we proposed three novel architectures using RNN to deal with semantic Segmentation and evaluated on the CityScapes dataset. All three architectures outperformed baseline and shown improvement in both Pixel Accuracy and IOU score.

We showed that our proposed architectures have shown improvement in efficiently segmenting the edges and boundaries. We also showed that there is a trade-off between using RNNs and Inference time. If we use RNNs to improve the performance of Semantic Segmentation Networks, then we need to trade off some extra seconds during the inference of the model.

In conclusion, if we apply Neural Network Pruning methods to our proposed model and reduce the Inference time, our finds will help advance the Autonomous Driving field. But, our finds will contribute in the advancement of Bio-medical Image segmentation, where doctors can trade-off those extra inference time for better performance. We showed the empirical results to support our claims.

Keywords: Image Segmentation, Deep Learning, Convolutional Neural Networks, Recurrent Neural Networks, Encoder-Decoder Models, and Scene Understanding.   
