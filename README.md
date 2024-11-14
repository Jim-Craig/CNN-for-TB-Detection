# CNN-for-TB-Detection
### Introduction
In this project we have used CNN for TB detection using X-ray images. We have worked
on one models which is MobileNet. The performances have been recorded in terms of
accuracy, sensitivity and loss for the publicly available Shenzen dataset and have
compared our results with the previous existing works. We will further discuss in detail
about the methodology used and implementation of the model in the later sections.

### Dataset-Collection
For tuberculosis detection, we have used a dataset named “Shenzhen Hospital X-ray
Set”. The Shenzhen dataset was collected in collaboration with Shenzhen No.3
People’s Hospital, Guangdong Medical College, Shenzhen, China.

### Preprocessing
For the preprocessing of the images we have used the CLAHE (Contrast Limited
Adaptive Histogram Equalization) algorithm to equalize images. CLAHE is a variant
of Adaptive histogram equalization (AHE) which takes care of over-amplification of
the contrast.

### Model
For this project we will be using a model using MobileNet model architecture as a
backbone for the training process. As the name applied, the MobileNet model is
designed to be used in mobile applications, and it is TensorFlow’s first mobile
computer vision model. MobileNet uses depth wise separable convolutions. It
significantly reduces the number of parameters when compared to the network with
regular convolutions with the same depth in the nets. This results in lightweight deep
neural networks.


### Result
![image](https://github.com/user-attachments/assets/8a59825e-7763-4851-a41a-ca3dd5abb519)
