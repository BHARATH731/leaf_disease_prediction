
# Leaf 🌿 Disease 🐛 Prediction 🔎

Plant Disease Detection is an innovative machine learning project that harnesses the power of Convolutional Neural Networks (CNN) and deep learning techniques to identify and classify diseases in plants. The primary objective is to offer farmers and agricultural experts a valuable tool for swift plant health diagnosis, facilitating timely intervention and minimizing the risk of crop loss.

[Live Project](https://leaf-disease-prediction.streamlit.app/)


## Project Structure 📂

The project comprises essential components:

- Plant_Disease_Detection.ipynb: Jupyter Notebook with the code for model training.
- app.py: Streamlit web application for plant disease prediction.
- plant_disease_model.h5: Pre-trained model weights.
- requirements.txt: List of necessary Python packages.
## Installation 🚀

To run the project locally, follow these steps:

1. Clone the repository:
```http
  https://github.com/BHARATH731/leaf_disease_prediction.git
```
2. Navigate to the project directory:
```
cd  leaf_disease_prediction
```
3. Install the required packages:
```
pip install -r requirements.txt
```
## Deployment

To deploy this project in local machine:

```
  streamlit run app.py
```


## Usage 🌿

After deploying the application, open your web browser and navigate to http://localhost:8501. Upload an image of a plant leaf, and the system will predict if it is affected by any disease.
## Model Training 🧠

The model was trained using the ```Plant_Disease_Detection.ipynb``` notebook. It employs a Convolutional Neural Network architecture to classify plant images into different disease categories. The trained model weights are saved in ```plant_disease_model.h5```.
The accuray of cnn model is 99% and loss is 0.7.
## Web Application 🌐

The web application ```(app.py)``` empowers users to interact with the trained model. Upload plant images, and the application provides real-time predictions regarding the health of the plant.