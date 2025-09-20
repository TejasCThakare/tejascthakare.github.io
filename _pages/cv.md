---
layout: archive
title: "My CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

---

## Education

**Program** | **Institution/Board** | **%/CGPA** | **Year**  
--- | --- | --- | ---  
M.Tech. (Electrical Engineering) | IIT Madras, Chennai, India | 8.35/10 | 2023-25  
M.Sc. (Physics) | IIT Bhubaneswar, Odisha, India | 7.84/10 | 2021-23  
B.Sc. (Physics, Statistics and Math) | KTHM College (Pune University) | 87.26% | 2017-20  
Higher Secondary | Maharashtra State Board | 72.46% | 2017  
Secondary | Maharashtra State Board | 90.20% | 2015  

---

## Research Projects

### 1. 3D High Dynamic Range Reconstruction of Dynamic Images using Gaussian Splatting  
**Jun’24-May’25**  
(M.Tech / Guide: Prof. Kaushik Mitra) IIT Madras  
**Keywords:** 3D HDR Reconstruction, Point Clouds, Gaussian Splatting, NeRF, HDR  

- Researched Neural Radiance Fields (NeRF) and HDR-NeRF for dynamic 3D HDR scene reconstruction; identified limitations that motivated the adoption of the Gaussian Splatting approach. 
-  Designed dual-path 3D HDR reconstruction pipeline combining exposure stacking, 3D Gaussian Splatting, and
tone-mapping supervision; achieved PSNR 37.129 vs baseline 35.47, improving rendering fidelity and computational
efficiency
- Extended 4D Gaussian Splatting pipeline for 16-bit dynamic self-captured datasets; incorporated HexPlane for
spatio-temporal encoding and HDR-GS-inspired spherical harmonics for HDR color representation

### 2. Analysis and Implementation of Machine Learning Model on CERN’s Big Datasets  
**Jun’22-May’23**  
(M.Sc / Guide: Prof. Seema Bahinipati) IIT Bhubaneswar  
**Keywords:** Big Data Analysis, EDA, Machine Learning  

- Processed and analyzed CERN’s petabyte-scale datasets to extract key insights through EDA and feature engineering.
- Otimized model inputs and hyperparameters to enhance model performance for signal vs noise classification.
- Achieved ROC-AUC of 0.98, demonstrating robust classification of noise and signal in large-scale datasets. 

### 3. The Exponentially Changing Periodic Probability Density Function (PDF)  
**Nov’18-Mar’19**  
(B.Sc) K.T.H.M. College  
**Keywords:** Probability Distribution, Mathematical Statistics  

- Developed the Sinex distribution, a novel PDF with multiple peaks, using Laplace Transforms and MGF functions.  
- Derived the Sinex distribution’s mean and variance using the gamma function and Inverse Laplace Transforms.  
- Analyzed the Sinex distribution, showing it approximates the Gamma Distribution under certain conditions.  

---

## Personal Projects  

### 1. Attention-Guided Hybrid Retinex for Low-Light Image Enhancement  
**Keywords:** Attention, Image Enhancement, Computer Vision, PyTorch  

- Developed a deep learning model for low-light image enhancement using Retinex decomposition, attention mechanisms, illumination relighting, and image fusion.  
- Implemented multi-scale residual learning and attention-guided illumination refinement to achieve adaptive brightness correction, texture preservation, and color enhancement under challenging lighting.  
- Achieved **PSNR 21+** and **SSIM 0.8+** on the LOL-v1 benchmark with a complete PyTorch pipeline for training, inference, evaluation, and visualization.  

### 2. GAN-Based Multi-Exposure Image Generation for HDR Imaging  
**Keywords:** Generative AI, Deep Learning, GAN, CNN, HDR Imaging  

- Built a GAN model to predict full 5-level multi-exposure stacks from a single LDR input for HDR imaging and computational photography.  
- Designed a convolutional encoder–decoder generator with skip connections to generate photorealistic exposure variations simulating real-world camera bracketing.  
- Implemented a PatchGAN discriminator with adversarial training to ensure both global and local consistency in the predicted exposure stacks.  

### 3. Lung Cancer Detection Using CNN  
**Keywords:** Medical Imaging, Classification, Computer Vision, CNN, Healthcare  

- Developed a CNN model to classify microscopic histopathological lung tissue images, achieving **92% validation accuracy** for lung cancer detection.  
- Obtained **F1-scores of 97%, 87%, and 91%** for adenocarcinoma, squamous cell carcinoma, and large cell carcinoma, ensuring robust performance across cancer subtypes.  
- Improved model robustness and interpretability using regularization, data augmentation, and optimization strategies, validated with confusion matrices and classification reports.   

### 4. Autocorrect System  
**Keywords:** NLP, Text Processing 

- Engineered an autocorrect system that enhances text accuracy and user experience by suggesting correct words.  
- Increased data processing efficiency by 15% by developing a scalable Python script for handling large text files.  
- Devised a word variant production method to provide accurate spelling corrections by generating possible words.  

### 5. Movie Recommendation System  
**Keywords:** Data Preprocessing, Recommender Systems 

- Built a content-based movie recommendation system using 4,800+ movies to provide personalized suggestions.  
- Carried out data pre-processing and feature engineering on text and numerical data, thus boosting the accuracy.  
- System retrieves and ranks the top 10 similar movies using a similarity matrix, enhancing the user experience.  

### 6. Chatbot Creation  
**Keywords:** Intent Classification, Text Embeddings 

- Designed a Chatbot model using TensorFlow and Keras, achieving over 94% accuracy in intent classification.  
- Mapped user input patterns to specific intents using a JSON-based dataset, enabling content-aware responses.  
- Trained the model using embeddings, pooling, and dense layers, with the tokenizer and sequence padding.  

---

## Relevant Coursework

### 1. Pattern Recognition and Machine Learning (PRML) January 2024–April 2024  
(CS5691) IIT Madras  
- Built classification models like Naive Bayes, KNN, Logistic Regression, and Random Forest. Implemented Ridge, Lasso Regression, K-Means, PCA, DBSCAN, and GMM.  

### 2. Computational Photography January 2024–April 2024  
(EE5176) IIT Madras  
- Worked on image reconstruction and enhancement techniques including demosaicing, denoising, alpha matting, motion deblurring, and compositing. Explored concepts such as Bayer pattern processing, tone mapping, HDR imaging, coded aperture, and light field imaging in computational photography.  

### 3. Image Signal Processing (ISP) January 2024–April 2024  
(EE5157) IIT Madras  
- Performed image processing in Python: geometric transforms, mosaicing, shape from focus, invariant blurring, Otsu’s thresholding, and occlusion detection.  

### 4. Natural Language Processing January 2024–April 2024  
(CS6370) IIT Madras  
- Built a Python-based search engine with NLP modules (segmentation, tokenization, lemmatization, stopword removal, spell correction) using NLTK, TF-IDF, and WordNet for semantic query matching.  

### 5. Data Analysis & Visualization in R/Python/SQL (DAV) January 2024–April 2024  
(MA5755) IIT Madras  
- Built a neural network from scratch for handwritten digit recognition with 87% training and 86% test accuracy.  

### 6. Probability Foundations for Electrical Engineers July 2023 – November 2023  
(EE5110) IIT Madras  
- Explored probability theory from fundamentals (expectation, variance, distributions) to advanced topics including joint/multivariate distributions, variable transformations, LLN, and probabilistic inequalities.  

---

## Online Coursework

- Data Structures and Algorithms in Python  
- Computer Vision with OpenCV and Deep Learning  
- Machine Learning, Data Science and Deep Learning   

---

## Technical Skills  

- **Programming Languages:** Python, SQL, C++  
- **Libraries:** NumPy, Pandas, Matplotlib  
- **Deep Learning & ML:** Scikit-Learn, PyTorch, Keras, TensorFlow  
- **Cloud & DevOps:** GCP, Azure DevOps, Docker, MLOps  
- **NLP & Vision:** NLTK, spaCy, OpenCV, Pillow, scikit-image, imageio  

---

## Leadership & Responsibilities  

- **Teaching Assistant:** Designed quizzes and assignments for *Modern Computer Vision* course; supported 100+ students.  
- **Student Placement Coordinator:** Coordinated the placement season at IIT Bhubaneswar, handling over 200+ students.  
- **Assistant Coordinator, Counseling Service Team:** Guided over 80+ freshers on-campus at IIT Bhubaneswar.  

---

## Awards & Achievements  

- **Competitive Exam Achievements:** IIT-JAM 2021 (*Top 4%*), GATE 2023 (*Top 7%*).  
- **Poster Presentation:** First Prize at Sandip University, Nashik.  
- **Publications:** Published 3 scientific articles during B.Sc.  
