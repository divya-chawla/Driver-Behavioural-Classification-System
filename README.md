# Driver-Behavioural-Classification-System

### Goal:
The goal of the project is to build a system based on an artificial neural network that can accurately detect dangerous driving actions and possibly send warning signals to the driver in real-time to reduce the number of traffic incidents.

### Overview:
In order to complete the project, four high-level steps were required:
1. Conduct a literature review
2. Generate and process the training data
3. Build and train an artificial neural network 
4. Integrate the ANN on micro-computer with a camera feed installed in a vehicle

### Design:
There were two approaches followed to design the neural network model, each are implementations of a convolutional neural network.

1. A Binary classification model, which could classify an image as “safe” or “unsafe”
2. A Multi-class classification model which could classify an image with several specific tags:
    1. Safe :  The driver focuses on the road.
    2. Drink: The driver drinks water or other soft drink.
    3. Call: The driver talks on a mobile phone.
    4. Reach Back: The driver turns around to reach something from the back seats. 
    5. Text: The driver uses a mobile phone to text a friend or search information from the internet.

### Outcome:
1. After training our binary classification network achieved training accuracy of 99.1 % and validation accuracy of 97.8 %. However, it failed to perform better than random guessing on unseen test data.
2. After training our multi classification network achieved training accuracy of 97.8 % and validation accuracy of 96.6 %.

### Conclusion
1. Our designed system was capable of achieving over 95% accuracy on validation data.
2. The accuracy on unseen test data dropped to approximately 80%.
3. The false positive rate for safe driving predictions was around 3%.
4. The prediction delay is around 0.25 seconds, but predictions could preempt driver behaviour in some cases.




