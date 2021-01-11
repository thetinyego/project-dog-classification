# project-dog-classification
This project applies CNN - Convolutonal Neural Network to classify dog's breeds. The application is able to tell, from an image, whether it's a dog or a human. f a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

# Detects Human
In this section, we use OpenCV's implementation of Haar feature-based cascade classifiers to detect human faces in images.
OpenCV provides many pre-trained face detectors, stored as XML files on github. We have downloaded one of these detectors and stored it in the haarcascades directory. In the next code cell, we demonstrate how to use this detector to find human faces in a sample image.
### An example from the human detector
![humandetect](https://user-images.githubusercontent.com/75294484/104163008-83759900-53aa-11eb-8aba-9efbc7a824cb.png)

# Detects Dog
We use a pre-trained model (VGG19) to detect dogs in images.
The VGG19 model is able to predict dog images with 88% accuracy.

# The results
<img width="374" alt="Screen Shot 2021-01-11 at 1 20 45 AM" src="https://user-images.githubusercontent.com/75294484/104163531-6e4d3a00-53ab-11eb-9794-a6c93ef75e5e.png">
<img width="343" alt="Screen Shot 2021-01-11 at 1 21 17 AM" src="https://user-images.githubusercontent.com/75294484/104163535-70af9400-53ab-11eb-808d-9f57d6fbe291.png">
<img width="412" alt="Screen Shot 2021-01-11 at 1 21 33 AM" src="https://user-images.githubusercontent.com/75294484/104163540-72795780-53ab-11eb-81d2-9f45d7ea4289.png">
<img width="471" alt="Screen Shot 2021-01-11 at 1 21 44 AM" src="https://user-images.githubusercontent.com/75294484/104163541-74431b00-53ab-11eb-9f64-f01e63ac8405.png">
<img width="250" alt="Screen Shot 2021-01-11 at 1 21 50 AM" src="https://user-images.githubusercontent.com/75294484/104163547-760cde80-53ab-11eb-9243-43bb3fad29ea.png">
<img width="295" alt="Screen Shot 2021-01-11 at 1 22 01 AM" src="https://user-images.githubusercontent.com/75294484/104163553-773e0b80-53ab-11eb-8a2b-e06acc34f7cb.png">

