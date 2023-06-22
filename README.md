# Sign Language Ai Classifier

<img width="552" alt="Screenshot 2023-06-21 at 11 29 20 PM" src="https://github.com/Sebas102507/SignLanguageAiClassifier/assets/52805660/52409b4c-28be-4dc5-9ec2-de3ed54f8519">


The project uses the "sign-language-mnist" dataset, which contains images of 25 signs of sign language, each with its respective label. In this project three approaches were implemented using convolutional networks to classify signs of sign language.
The first approach is to train a convolutional network from scratch, which involves designing and training the neural network architecture without using transfer learning techniques. The convolutional network learns directly from the images in the dataset and adjusts for the specific characteristics of signs in sign language.
In the second approach, transfer learning is used, which involves leveraging a pre-trained neural network on a different data set. A pre-trained convolutional network, such as VGG16 or ResNet, is selected, and the latter network components are adjusted to fit the sign language dataset. This allows you to take advantage of the prior knowledge of the pre-trained network and speed up the training process.
In the third approach, transfer learning is used with the MobileNet V2 convolutional network. MobileNet V2 is an efficient architecture designed for computer vision tasks on mobile devices. By leveraging pre-trained MobileNet V2 on a large dataset, it can be used as a solid foundation for classifying the signs of sign language in this project.


<img width="580" alt="Screenshot 2023-06-21 at 11 29 30 PM" src="https://github.com/Sebas102507/SignLanguageAiClassifier/assets/52805660/11f450e6-cfd8-4735-8068-b2f0052185a8">
