# Train-and-Deploy-a-CNN-Model-Using-TensorFlow-Serving

Objective: 
Build a CNN model using distributed training to detect diabetic retinopathy and deploy it using TensorFlow Serving.
 
Problem Statement:
 You are a Computer Vision Engineer at health.ai. Your company is developing a deep learning application to automate the detection of diabetic retinopathy. The company is collecting high-resolution retina image data from various clinical partners. However, the dataset is expected to be enormous and cannot be stored on a central system. You have been assigned the task of building a proof of concept using the Kaggle retinopathy dataset. Your goal is to train a CNN model with the Mirrored Strategy and deploy it with TensorFlow Serving.
 
Dataset Details:
 The dataset comprises a large collection of high-resolution retina images captured under various imaging conditions. For each subject, both left and right fields are provided. The images are labeled with a subject ID and designated as either left or right. A clinician has rated the presence of diabetic retinopathy in each image on a scale of 0 to 4. Like any real-world dataset, there may be noise in both the images and labels. The images might contain artifacts, be out of focus, underexposed, or overexposed.
