# 🍎🥕 Fruit and Vegetable Image Classification

This project builds a binary image classification model to distinguish between **fruits** and **vegetables** using a deep learning model trained on the [Kaggle Fruit and Vegetable Image Recognition Dataset](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition).

---
![Screenshot (790)](https://github.com/user-attachments/assets/18a2b692-793c-477c-9705-00dd33efef00)
![Screenshot (792)](https://github.com/user-attachments/assets/b6ab3ee1-d40d-4365-a80f-f1e5a8e82af8)
![Screenshot (793)](https://github.com/user-attachments/assets/d32946a6-925b-4f35-83e1-4dc6980f78f1)
![Screenshot (794)](https://github.com/user-attachments/assets/297e8954-a381-4533-adba-72967b388d02)



## 📂 Dataset

- **Source**: [Kaggle - Fruit and Vegetable Image Recognition](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)
- **License**: CC0 1.0
- **Size**: ~2GB
- **Classes**: 36 (split manually into two categories: fruits and vegetables)

---

## 📌 Project Overview

We used a **Convolutional Neural Network (CNN)** to perform binary classification between fruits and vegetables by:
- Preprocessing the dataset
- Organizing it into binary folders
- Creating a CNN model with Keras
- Training and evaluating the model

---

## 📊 Precision

In this binary classification task, **precision** measures the accuracy of the model when it predicts an image as a specific class (e.g., fruit or vegetable).

> **Precision = True Positives / (True Positives + False Positives)**

We achieved a **precision score of approximately 92%**, which means:

- When the model predicts an image as a fruit (or vegetable), it's correct **92% of the time**.
- This high precision indicates **low false positives**, meaning the model rarely misclassifies one category as the other.
- It is especially useful in scenarios where incorrect classification (e.g., labeling a vegetable as a fruit) could lead to poor downstream decisions or confusion in a real-world application.

The model has been evaluated using classification reports and confusion matrices to ensure that precision, recall, and F1-score are balanced.

---

## 🚀 Future Improvements

To enhance the performance and usability of the model, the following improvements can be considered:

1. **Data Augmentation**: Apply random transformations like flipping, zooming, and rotation to improve model robustness.
2. **Model Tuning**: Adjust hyperparameters (like learning rate, dropout rate, and number of filters) for better results.
3. **Transfer Learning**: Use pre-trained models like VGG16 or MobileNet for improved accuracy with fewer data.
4. **Web Integration**: Build a user-friendly interface using tools like Streamlit or Flask where users can upload an image and receive predictions in real-time.
5. **Multi-class Classification**: Extend the model to classify specific fruit and vegetable types rather than just binary classification.

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute the code, provided that the original author is credited.

---

## 🙋‍♀️ Author

**Rifana Sherin**  
A passionate learner in the fields of **Machine Learning**, **Data Analytics**, and **AI**.  
Currently exploring real-world ML applications through beginner-friendly projects.

📫 [LinkedIn Profile](https://www.linkedin.com/in/rifanasherin)  
🧠 Always open to collaboration and learning new things!



