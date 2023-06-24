# dry_beans_classiification
This project aims to classify different types of dry beans
Project Description:
The aim of this project is to develop a machine learning model for classifying different types of dry beans based on their visual characteristics. The project utilizes computer vision techniques to extract features from high-resolution images of dry bean grains and applies a multiclass classification algorithm to accurately identify the variety of each bean.

The dataset used in this project consists of images of 13,611 grains of seven different registered dry bean varieties. These beans possess similar features in terms of form, shape, type, and structure, making their classification challenging. The dataset provides a comprehensive set of attributes, including 12-dimensional measurements and four shape forms, enabling the development of a robust classification model.

The project follows a multiclass classification approach, where the model needs to classify each dry bean into one of the seven registered varieties. The dataset is preprocessed by segmenting the bean images and extracting 16 relevant features. These features capture the distinguishing characteristics of each bean, which will be used as inputs for the classification model.

To build the classification model, the project utilizes the Support Vector Machine (SVM) algorithm. The extracted features are scaled using the StandardScaler to ensure consistent input ranges. The dataset is then split into training and testing sets, with 80% of the data used for training and 20% for evaluation. The SVM model is trained on the training set and evaluated using various classification metrics on the test set, such as precision, recall, and F1-score.

The project implementation is carried out in Python, leveraging popular libraries such as pandas, scikit-learn, and OpenCV. The pandas library is used to load and manipulate the dataset, while scikit-learn provides essential functionalities for data preprocessing, model training, and evaluation. OpenCV is utilized for computer vision tasks such as image segmentation and feature extraction.

The final outcome of the project is a trained SVM model capable of accurately classifying dry bean grains into their respective registered varieties. The model's performance is assessed through classification metrics, enabling a comprehensive evaluation of its effectiveness. The developed model can be utilized to automate the seed classification process, assisting farmers and researchers in ensuring uniformity and quality control of dry bean varieties.

Overall, this project demonstrates the application of machine learning and computer vision techniques to solve a real-world problem in the agricultural domain, offering an efficient and accurate solution for dry bean classification.




