# Laboratory-Work-3-Activity-Building-a-Custom-Image-Classifier-with-TensorFlow-
Building a Custom Image Classifier with TensorFlow Using Personal Image Datasets from Google Drive

# Google Collab Link:
https://colab.research.google.com/drive/1yXe61B-xkcl_-B8W2zLADj5qXHms1Uzd?usp=sharing

# Guide Questions (Student Reflection & Explanation)
1. Dataset Preparation<br><br>

○ How did you organize your dataset in Google Drive?<br>
- I organized my dataset by creating a main folder in Google Drive and separating the images into subfolders based on their categories or labels. Each folder contains images that belong to the same class, which makes it easier for the model to identify and learn patterns from the data.<br><br>

○ Why is folder structure important for TensorFlow image loading?<br>
- Folder structure is important because TensorFlow automatically uses the folder names as labels for the images. This helps the system correctly classify the images during training and makes the dataset easier to manage.<br><br>

2. Model Training<br><br>

○ What is the role of convolutional layers in image classification?<br>
- Convolutional layers help the model detect important features in an image such as edges, shapes, textures, and patterns. These features allow the model to understand and recognize what object is present in the image.<br><br>

○ Why do we split data into training and validation sets?<br>
- We split the data so the model can learn from the training set and then be tested on the validation set. This helps evaluate how well the model performs on new data and prevents overfitting.<br><br>

3. Performance Analysis<br><br>

○ What accuracy did your model achieve?<br>
- The model achieved an accuracy of around 87.79% during validation, which indicates that the model can correctly classify most of the images.<br><br>

○ How did the number of images affect the model’s performance?<br>
- The number of images affects how well the model learns. A larger dataset usually improves the model’s performance because it provides more examples for the model to learn from.<br><br>

4. Critical Thinking<br><br>

○ What challenges did you encounter while using your own dataset?<br>
- One challenge was collecting enough images for each category and making sure they were clear and properly labeled. Another issue was that some images had different lighting or backgrounds, which made the training process more difficult.<br><br>

○ How can data augmentation improve your model?<br>
- Data augmentation improves the model by creating variations of existing images, such as rotating, flipping, or zooming them. This helps increase the dataset size and makes the model more robust and accurate.<br><br>

5. Application<br><br>

○ Suggest a real-world application for your trained model.<br>
- A real-world application of this model could be an automated image recognition system, such as identifying objects, classifying products, or detecting diseases from medical images.<br><br>

○ How can this system be integrated into a mobile or web application?<br>
- The trained model can be integrated into a mobile or web application by connecting it to the app’s backend. The application can allow users to upload or capture images, and the system will analyze the image and return the classification result in real time.<br><br>

# Activity 3A: Improving and Evaluating a Custom Image Classifier
# Enhancing Model Performance: Visualization, Overfitting Control, Data Augmentation, and Model Deployment

