# Udacity-ML-capstone-project
Cat vs Dog image classifier using TensorFlow.
<br><br>
The Udacity Machine Learning Engineer Nanodegree is completed when the capstone project is being completed. The choice of the subject is made by the student. The challenge must use knowledge and competences developed during the chosen specialization, in this case Deep Learning using Google's open source machine learning framework TensorFlow.
<br><br>
The aim of this project is to develop an image classifier to distinguish images of cats from images of dogs. It is directly inspired from <a href="https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition">this Kaggle competition</a>. The used dataset is its "train" zip composed of 25000 labeled images of dogs and cats.
<br><br>
Please read the report (Report.pdf) to understand the differents steps of the project development.
<br><br>
The code is composed of two IPython Notebooks. One for data exploration to extract, analyse and prepare the information associated to the images (data-exploration.ipynb). Another for building, training and evaluating the classifier (cat-or-dog-identifier.ipynb).
<br><br>
If you want to use the code, please follow the steps :
<br>- Download the images of the train .zip file <a href="https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data">here</a> and unzip them into the "images" folder. Delete the file "images/file-to-make-folder-exist.txt".
<br>- Execute the data exploration IPython Notebook.
<br>- Use the identifier IPython Notebook to make trainings or predictions. Please notice the parameter "use_saved_model" if you want to use an already trained model and "save_model" if you want to save it for later. Be careful with "checkpoint_file_name" not to overwrite the saved models.
<br><br>
Good luck, have fun !
