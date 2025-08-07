# Real-Time Wildfire Detection using Deep Learning  
A deep learning-based system for automatic wildfire detection in real time using a modified VGG16 Convolutional Neural Network (CNN). This project is designed to support early intervention by identifying wildfires from camera feeds or images with high accuracy and reliability.  

## Overview  
Wildfires are becoming increasingly frequent and devastating due to climate change.Early detection is crucial for minimizing damage. Traditional detection methods (satellites, patrols, aerial surveillance) suffer from latency, limited visibility, or high operational cost.  
This project leverages deep learning and computer vision to build an efficient real-time wildfire detection system capable of distinguishing between fire and non-fire images with over 95% accuracy.  

## Features    
🔍 Fire vs Non-Fire Image Classification  	
🧠 Modified VGG16 (Reduce-VGGNet) for optimized performance  
⚙️ Custom GUI for real-time detection and visualization  
📸 Supports live video feeds or static image input  
📊 Precision/Recall prioritized to minimize false negatives  
🧪 Evaluation metrics include accuracy, F1-score, confusion matrix  
🔁 Data augmentation and preprocessing for robustness  
⚡ Fast, lightweight, and deployable on resource-limited systems  

## 🛠️ Tech Stack 
Python    
TensorFlow / Keras  
OpenCV  
Matplotlib / Seaborn  
Tkinter (for GUI)  

## ✅ Key Takeaways  
Real-time detection is achievable with lightweight CNNs like Reduce-VGGNet.  
Prioritizing recall reduces the chance of missing fires—critical in emergency use cases.  
The model is robust to various conditions due to data augmentation.  
The GUI makes the system practical and accessible for emergency teams.  
