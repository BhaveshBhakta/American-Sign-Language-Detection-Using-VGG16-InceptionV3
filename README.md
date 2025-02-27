## **American Sign Language (ASL) Alphabet Classification Using Deep Learning**  

### **Project Overview**  
This project focuses on classifying American Sign Language (ASL) alphabet gestures using deep learning techniques. The dataset, sourced from Kaggle, consists of images representing different ASL signs. The model is trained using **CNN-based architectures**, including a custom CNN and a transfer learning approach with **InceptionV3**. Data augmentation techniques are applied to improve generalization.

### **Key Features**  
- **Dataset Handling**: The dataset is downloaded from Kaggle and processed for training, validation, and testing.  
- **Data Splitting**: Stratified train-test-validation splitting ensures class balance.  
- **Data Augmentation**: Image transformations (rescaling, flipping) enhance model robustness.  
- **CNN Architecture**: A custom CNN model is built with **Conv2D, MaxPooling2D, Flatten, Dense, and Dropout** layers.  
- **Transfer Learning with InceptionV3**: Uses a pre-trained model to extract features and improve classification accuracy.  
- **Performance Evaluation**: Achieves high accuracy using categorical cross-entropy loss and Adam optimizer.  

### **Purpose**  
The main objective of this project is to develop an **AI-powered ASL recognition system** that can **automatically interpret hand gestures** from images. This helps bridge communication gaps for the hearing and speech impaired by enabling real-time gesture translation.

### **Applications**  
- **Assistive Technology**: Enhances communication for individuals with hearing or speech disabilities.  
- **Educational Tools**: Used for training sign language learners.  
- **AI in Accessibility**: Can be integrated into mobile apps or smart devices for real-time ASL translation.

  ## Installation

### Clone the Repository:

```bash
git clone https://github.com/BhaveshBhakta/American-Sign-Language-Detection-Using-VGG16-InceptionV3.git
```

### Navigate to the Project Folder:

```bash
cd American-Sign-Language-Detection-Using-VGG16-InceptionV3
```


### Run the Jupyter Notebook or Python Script:


## Collaboration
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.
