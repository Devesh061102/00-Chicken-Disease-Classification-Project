# Chicken-Disease-Classification

This project focuses on using deep learning techniques to detect diseases in chickens at an early stage. The goal is to prevent mortality, reduce farmers' losses, and promote public health by developing an intelligent system that can classify chickens as "Coccidiosis" or "Healthy."

## Flask app

![App](https://github.com/Devesh061102/00-Chicken-Disease-Classification-Project/blob/main/images/coccidiosis.png?raw=true)
![App](https://github.com/Devesh061102/00-Chicken-Disease-Classification-Project/blob/main/images/healthy.png?raw=true)

## Roadmap
**Objective**: The main objective of the project is to develop a system for the early identification of various diseases in chickens.

**Data Collection**: The project starts with collecting a dataset of chicken images labeled as "Coccidiosis" or "Healthy".

**Dataset Organization**: 
- `train/`: Contains subdirectories for "Coccidiosis" and "Healthy" with images.
- `validation/`: Contains subdirectories for "Coccidiosis" and "Healthy" with images.
- `test/`: Contains subdirectories for "Coccidiosis" and "Healthy" with images.

**Preprocessing**: The collected data is preprocessed to make it suitable for training and testing.

**Model**: The VGG16 model from Keras Applications is used for categorical classification of "Coccidiosis" and "Healthy".

**Training the Model**:
1. Load and preprocess the dataset.
2. Define the VGG16 model.
3. Compile the model.
4. Train the model on the training set and validate it on the validation set.
5. Save the trained model.

**Evaluation**: Evaluate the model on the test set using metrics like accuracy, precision, recall, and F1-score.

**Model Deployment**: The best-performing model is deployed using Flask, a lightweight web server gateway interface (WSGI) web application framework. This allows the model to be accessed via a simple web interface, enabling real-time predictions.

Overall, this project aims to improve the health and productivity of chickens by providing early disease detection.

## Lessons Learned

This project provided valuable experience in applying deep learning concepts to a real-world problem. It was particularly interesting to see how deep learning models can effectively classify images and the impact of preprocessing on model performance.

I’m excited about the potential applications of this project and look forward to exploring more ways to leverage deep learning in agriculture. 💡

## Authors

- [@devesh](https://github.com/Devesh061102)


# Hi, I'm Devesh! 👋


## 🚀 About Me
I'm a Full Stack Data Scientist


## 🛠 Skills
1. C, C++, Python
2. SQL
3. Machine Learning
4. Deep Learning
5. Data Science