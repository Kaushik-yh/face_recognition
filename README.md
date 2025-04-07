# face_recognition
Face recognition app for automated employee attendance

# Product Description/Objective
An AI face recognition app for automated employee attendance uses advanced facial recognition technology to accurately and efficiently track employee attendance. By simply scanning employees' faces upon arrival and departure, the app eliminates the need for traditional timecards or biometric devices, reducing errors and fraud. It provides real-time attendance data, enhances workplace security, and streamlines HR processes for greater productivity and accuracy.       

# How does it work ?
Our app leverages Google's advanced **Vision Transformer (ViT)** architecture, trained on the **LFW (Labeled Faces in the Wild) dataset**, to deliver highly accurate employee attendance tracking through facial recognition. The AI model intelligently extracts distinct facial features and compares them to the stored data of registered employees. When an employee’s face is scanned, the model analyzes the key features, and a confidence score is generated. A high score indicates a match, confirming the employee’s identity and marking their attendance automatically. This seamless, secure process ensures precise tracking while minimizing errors and enhancing workplace efficiency. 

# About the architecture.
The Vision Transformer (ViT) is a deep learning architecture designed for image classification tasks, which applies transformer models—originally developed for natural language processing (NLP)—to images. ViT divides an image into fixed-size non-overlapping patches. Each patch is flattened into a 1D vector, which is then linearly embedded into a higher-dimensional space. The patch embeddings are processed using a standard transformer encoder. This consists of layers with multi-head self-attention and feed-forward networks. The transformer is capable of learning global dependencies across the entire image. The Vision Transformer outperforms traditional convolutional neural networks (CNNs) on large-scale datasets, especially when provided with sufficient training data and computational resources.

# About the Dataset. 
Labeled Faces in the Wild (LFW) is a well-known dataset used primarily for evaluating face recognition algorithms. It consists of a collection of facial images of famous individuals from the web. LFW contains 13,000+ labeled images of 5,749 different individuals. The faces are collected from various sources, with images often showing individuals in different lighting, poses, and backgrounds. LFW is typically used for face verification and face recognition tasks. The goal is to determine if two images represent the same person or not.

