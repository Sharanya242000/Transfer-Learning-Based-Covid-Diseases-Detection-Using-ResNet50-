# Transfer-Learning-Based-Covid-Diseases-Detection-Using-ResNet50-

INTRODUCTION:

A coronavirus (SARS-CoV-2) outbreak began on December 31, 2019 in Wuhan, the capital of Hubei Province in central China. The World Health Organization (WHO) announced a global health emergency on January 30, 2020, and the World Health Organization (WHO) declared pandemic on March 11, 2020, after some hesitation. By 14 April 2020, there have been a total of 1,985,135 confirmed cases and 125,344 deaths. The United States has taken on a new role as a global hotspot of 605,354 cases and 25,394 deaths have been registered as of April 14, 2020. COVID-19 pathogenesis is being studied by researchers from several disciplines, as well as public health professionals and develop measures for controlling. Imaging patterns on chest radiography and computed tomography (CT) for individuals diagnosed with COVID-19 have recently been discovered. Infected patients in Wuhan had bilateral lung opacities on 40 out of 41 (98 %) chest CTs, with lobular and subsegmental regions of consolidation being the most common findings. Other researchers discovered significant rates of ground-glass opacities and consolidation, with a rounded shape and peripheral lung distribution in some cases. Patients suspected of COVID-19 infection generally require a thoracic radiology examination. Early detection and diagnosis of the condition are critical in ensuring prompt treatment.


Convolutional Neural Network:

The Convolutional Neural Network is one of the most widely used deep neural networks (CNN). Convolution is a mathematical linear action between matrices that gives it its name. Convolutional layer, non-linearity layer, pooling layer, and fully-connected layer are some of the layers of CNN. Pooling and non-linearity layers do not have parameters, whereas convolutional and fully-connected layers have. In machine learning issues, the CNN performs admirably. Particularly impressive were the applications that deal with picture data, such as the world's largest image classification data collection (Image Net), computer vision, and natural language processing (NLP), with the results obtained.
Due to the availability of large-scale annotated datasets and deep convolutional neural networks, significant progress has been made in picture recognition (CNNs). From a significant amount of training data, CNNs may learn data-driven, highly representative, hierarchical image characteristics. In the medical imaging area, however, acquiring datasets with as much detail as ImageNet is a difficulty. There are currently three basic strategies for successfully using CNNs to medical image classification: training the CNN from scratch, using pre-trained CNN features off the shelf, and undertaking unsupervised CNN pre-training with supervised fine-tuning. Transfer learning, or fine-tuning CNN models trained on natural image datasets for medical imaging tasks, is another effective strategy.


Residual network (ResNet):

In transfer learning, AlexNet, AlexNetOWTBn, GooLeNet, Overfeat, and VGG models are more frequent. Many convolutional layers were stacked. Deep CNN networks have a number of challenges, including network optimization, the vanishing gradient problem, and degradation issues.The residual network (ResNet) is useful for solving difficult problems and improving detection accuracy. ResNet aims to address the challenges of deep CNN training, like as saturation and accuracy loss. Because it is relatively easy to improve and provides higher accuracy, ResNet is a superior deep learning architecture. There's also the issue of declining gradient, which can be avoided by using the network's skip connections. The network's temporal complexity increases as the number of layers in the deep network architecture increases. A bottleneck design can help to simplify things. As a result, we decided to build our framework using the ResNet50 pre-trained model rather than other pre-trained networks with additional layers. Further down, the architecture is fully defined.



The main components of ResNet50 are convolutional layers, Activation unit, pooling, batch normalization. 

a) Convolution layer: Convolution layers in neural networks are responsible for extracting specific information from the input images. Filters are used in a sequential order to accomplish this convolution. From the input photos, this layer generates feature maps.

b) Activation function: A transformation is applied to the output of each convolution layer in a convolution neural network. This is so that nonlinearity can be incorporated into the framework. The ReLU function is a prominent activation function. This ReLU has a low computing cost and good gradient convergence compared to other activation functions. If the input is negative, the output of ReLU is zero, but if the input is positive, the output equals the input.

c) Pooling Layer: The feature maps obtained from convolution operations are summarised using a pooling layer. This layer decreases the number of parameters taken into account during the training procedure. This also assures that the computation time is reduced. This layer also aids in the regulation of the over-fitting process. In the case of max-pooling, the output is the input element's maximum value. The output of average pooling, on the other hand, is the mean value of the input element.

d) Batch normalization layer: The goal of the batch normalization test is to increase convergence quality throughout the training period. The output of the previous layer is regularized in this layer. This layer has the benefit of allowing for a faster learning rate.



