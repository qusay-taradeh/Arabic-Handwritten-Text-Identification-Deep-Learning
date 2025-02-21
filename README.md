# Arabic-Handwritten-Text-Identification-Deep-Learning  
Deep learning approach for identifying Arabic handwritten text using CNN techniques.

## Summary  
Implementation of a deep learning solution for Arabic handwritten text identification. This project builds on local feature extraction methods by developing custom CNN models, applying data augmentation, and leveraging well-known architectures and transfer learning. Each stage is evaluated through loss and accuracy metrics, allowing for a comprehensive comparison of model performance.

## Specifications  
This application should be able to perform the following tasks:

1. **Task 1: Custom CNN Network**  
   - **Architecture Design:**  
     - Define the number of layers (starting with 1-2 convolutional layers, increasing complexity as needed).  
     - Incorporate various types of layers (convolutional, pooling—max/average/global, fully connected, and specialized layers such as dropout and batch normalization).  
     - Select appropriate activation functions (e.g., ReLU, sigmoid, tanh).  
   - **Convolutional & Pooling Parameters:**  
     - Set the number of filters, filter sizes (e.g., 3x3 or 5x5), stride, and padding for convolutional layers.  
     - Choose pool size (e.g., 2x2 or 3x3) and pool type for pooling layers.  
   - **Fully Connected & Training Hyperparameters:**  
     - Determine the number of neurons, learning rate, batch size, epochs, optimizer (e.g., Adam, SGD, RMSprop), and regularization methods.  
   - **Model Evaluation:**  
     - Train various models with hyperparameter tuning, then plot Loss vs. Epoch and accuracy for each model.
   
2. **Task 2: Data Augmentation**  
   - Retrain the selected custom CNN model from Task 1 using data augmentation techniques relevant to the dataset.  
   - Plot and compare the Loss vs. Epoch and accuracy metrics with those obtained in Task 1.

3. **Task 3: Published CNN Architecture**  
   - Choose a well-known CNN architecture (e.g., VGG, ResNet) and train it with data augmentation.  
   - Plot Loss vs. Epoch and accuracy, then compare these results with the performance of the custom CNN from Task 2.

4. **Task 4: Transfer Learning**  
   - Utilize a pre-trained CNN model on a similar task and fine-tune it on the given dataset using appropriate transfer learning methods.  
   - Plot Loss vs. Epoch and accuracy, and compare these results with those from Task 3.

## Authors
Qusay Taradeh, Karim Marayta
