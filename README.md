# Facial_Recognition
### Facial recognition is a technology that uses biometric software to identify or verify an individual by analyzing and comparing patterns in their facial features. This technology has gained widespread attention in recent years due to its growing use in security and surveillance systems, as well as its potential applications in various industries, including healthcare, retail, and entertainment. Facial recognition can provide an extra layer of security for sensitive locations, such as airports or government buildings, by quickly and accurately identifying individuals. We are developing our model by developing a multilayer convolutional neural network which will be trained with user images and tested and validated by the model . We have gained more than 80% accuracy in the model and are working to achieve greater accuracy further. 

## Tech Stack Used :
### Libraries Used : Tensorflow , opencv , keras , matplotlib ,os, CVZone , Sklearn . 
## Process or methodology : 

### Face Detection: The first step in facial recognition is detecting the face in an image or video frame. Face detection algorithms use pattern recognition techniques to locate faces in an ### image.

### Face Alignment: Once the face is detected, the next step is to align the face to a standard position. This involves locating the facial landmarks such as eyes, nose, and mouth and ### ### rotating and scaling the face to a standard orientation.

### Feature Extraction: After alignment, the system extracts the facial features from the aligned face. These features may include the distance between the eyes, the shape of the nose, and ### the curvature of the lips.

### Face Representation: The extracted features are converted into a mathematical representation or a feature vector. This feature vector is a compact representation of the facial features ### and is used for comparison and identification.

### Face Matching: In the final step, the feature vector is compared with the feature vectors of the individuals in the database to find a match. This involves computing the similarity score ### between the feature vectors and selecting the one with the highest score.

## Procedure :
### 1. Setup
### 1.1 Install Dependencies
### 1.2 Import Dependencies
### 1.3 Set GPU Growth
### 1.4 Create Folder Structures


### 2. Collect Positives and Anchors
### 2.1 Untar Labelled Faces in the Wild Dataset
### 2.2 Collect Positive and Anchor Classes
### 2. x NEW - Data Augmentation

### 3. Load and Preprocess Images
### 3.1 Get Image Directories
### 3.2 Preprocessing - Scale and Resize
### 3.3 Create Labelled Dataset
### 3.4 Build Train and Test Partition

### 4. Model Engineering
### 4.1 Build Embedding Layer
### 4.2 Build Distance Layer
### 4.3 Make Siamese Model

### 5. Training
### 5.1 Setup Loss and Optimizer
### 5.2 Establish Checkpoints
### 5.3 Build Train Step Function
### 5.4 Build Training Loop
### 5.5 Train the model

### 6. Model Evaluation
### 6.1 Import Metrics
### 6.2 Make Predictions
### 6.3 Calculate Metrics
### 6.4 Viz Results

### 7. Save Model

### 8. Real-Time Test
### 8.1 Verification Function
### 8.2 OpenCV Real-Time Verification



