# Plant-Disease-Detection 
Plant disease detection is crucial for every farmer, and to address this need, we have developed a deep learning-based system. This system utilizes convolutional neural networks (CNNs) to classify leaf images into 39 different categories. The convolutional neural network model is built using the PyTorch framework. For training the model, we employ the PlantVillage dataset, which provides a diverse set of leaf images for accurate classification. This approach helps in the early detection and management of plant diseases, potentially increasing crop yield and farming efficiency.

## Run Project in your Machine
* You must have **Python3+** installed in your machine.
* Install all the dependencies using below command
    `pip install -r requirements.txt`
* Go to the `Flask-Deployed-App` folder.
* Download the pre-trained model file `plant_disease_model_1.pt` from [here](https://drive.google.com/file/d/1yzNs-LFl3V4BsoVqz4Vw6YSDZgYeziwV/view?usp=sharing)
* Add the downloaded file in `Flask Deployed App` folder.
* Run the Flask app using below command `python app.py runserver`
* You can also use downloaded file in `Model` Section and play with it using Jupyter Notebook.


## Testing Images

* If you do not have leaf images then you can use test images located in test_images folder
* Each image has its corresponding disease name, so you can verify whether the model is working perfectly or not


## Snippet of Web App :
#### Main page
<img src = "demo_images/Screenshot 2024-04-24 173322.png" > <br>

#### Results Page 
<img src = "demo_images/Screenshot 2024-04-24 173422.png"> <br>
