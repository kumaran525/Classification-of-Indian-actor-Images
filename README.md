<h3>Classifying Indian Actor Images</h3>

This project focuses on classifying Indian actor images using the FaceNet model for feature extraction and predicting using custom CNN and DNN models. The goal is to achieve high accuracy in classifying Indian actor images and evaluate the model's performance.

<h3>Data Source</h3>

The data for this project is obtained from [Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/indian-actor-images-dataset), a popular platform for data science competitions and datasets. Please refer to the provided Kaggle link to access the dataset used in this project.

<h3>Class Selection</h3>

Out of the total 135 classes available, the following 10 classes were selected for processing:

1. Nagarjuna Akkineni
2. Madhavan
3. Kamal Haasan
4. Saif Ali Khan
5. Mohanlal
6. Prabhas
7. Sanjay Dutt
8. Akshay Kumar
9. Ramya Krishnan
10. Salman Khan


<h3>Approach</h3>
<p><b>Exploratory Data Analysis (EDA)</b>: The EDA.ipynb notebook contains the exploratory data analysis process. It involves analyzing and visualizing the dataset to gain insights into its structure, distribution, and any patterns present in the actor images.</p>

<b>Feature Extraction</b>: The Feature_Extraction.ipynb notebook focuses on the feature extraction process. It utilizes the FaceNet model to extract facial features from the input images. These features are then used as input for the classification models.

<b>CNN Model</b>: The cnn.ipynb notebook contains the implementation of the custom CNN model. It includes the model architecture and returns the trained CNN model object.

<b>DNN Model</b>: The dnn.ipynb notebook focuses on the implementation of the custom DNN model. It includes the model architecture and returns the trained DNN model object.

<b>Preprocessing</b>: The preprocessor.ipynb notebook covers the preprocessing steps performed on the data. It includes normalization, resizing, and median filter to prepare the data for feature extraction and model training.

<b>Trainer Notebook</b>: The trainer.ipynb notebook serves as the central file to train and evaluate the CNN and DNN models. It imports the necessary functions or classes from the cnn.ipynb and dnn.ipynb notebooks, executes the training process, and evaluates the models on the test set.

<h3>Results</h3>

The CNN model achieved an accuracy of 70% on the test set. The results of the model evaluation, including metrics images and classification report, can be found in the results/ folder. The metrics images visualize the precision, recall, and F1-score for each class, providing an overview of the model's performance. 

Further improvements can be made to the model by considering the following steps:

<p>Adding more data: Increasing the amount of training data can help the model learn more diverse patterns and improve its generalization capabilities.</p>
Fine-tuning the model: Experimenting with different hyperparameters, model architectures, and regularization techniques can further enhance the model's accuracy and robustness.

Feel free to reach out if you have any questions or suggestions!
