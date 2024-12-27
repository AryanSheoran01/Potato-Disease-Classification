# Potato Disease Classification Using CNN

## Overview
This project focuses on developing an end-to-end deep learning solution to classify potato plant diseases using convolutional neural networks (CNN). The system provides an optimized pipeline for accurate predictions and scalable deployment, making it practical for real-world agricultural applications.

---

## Problem Statement
Diseases in potato plants can lead to significant crop losses, affecting food security and farmer incomes. Identifying these diseases at an early stage can mitigate damage and improve yield. This project leverages deep learning to classify images of potato plants into disease categories, providing an automated and efficient solution.

---

## Features
1. **Image Classification Model**:
   - Developed a CNN-based classification model using TensorFlow.
   - Enhanced model accuracy through data augmentation and TensorFlow datasets.

2. **Backend Development**:
   - Built a scalable backend server using FastAPI.
   - Integrated TensorFlow Serving for model deployment and API interaction.

3. **Performance Optimization**:
   - Optimized the model for mobile platforms using quantization and TensorFlow Lite.
   - Ensured low-latency predictions suitable for resource-constrained environments.

4. **Cloud Deployment**:
   - Deployed the solution on Google Cloud Platform (GCP).
   - Utilized Google Cloud Functions (GCF) for seamless scalability and high availability.

---
## Setup for Python:

1. Install Python 

2. Install Tensorflow Serving

## Setup for ReactJS

1. Install Nodejs
2. Install NPM 
3. Install dependencies

```bash
cd frontend
npm install --from-lock-json
npm audit fix
```


## Training the Model

1. Download the data from [kaggle](https://www.kaggle.com/arjuntejaswi/plant-village).
2. Only keep folders related to Potatoes.
3. Run Jupyter Notebook in Browser.

```bash
jupyter notebook
```

4. Open `training/potato-disease-training.ipynb` in Jupyter Notebook.
5. In cell #2, update the path to dataset.
6. Run all the Cells one by one.
7. Copy the model generated and save it with the version number in the `models` folder.



### Using FastAPI

1. Get inside `api` folder

```bash
cd api
```

2. Run the FastAPI Server using uvicorn

```bash
uvicorn main:app --reload --host 0.0.0.0
```

3. Your API is now running at `0.0.0.0:8000`



