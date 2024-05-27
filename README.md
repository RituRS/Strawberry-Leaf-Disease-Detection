# Strawberry Plant Disease Detection

This project aims to detect diseases in strawberry plants using deep learning techniques. It utilizes the PlantVillage dataset obtained from Kaggle, which contains images of various plant diseases and healthy plants, including strawberry plant diseases.

## Dataset Information

The PlantVillage dataset contains images collected by researchers at Pennsylvania State University. It consists of 2 classes, including healthy strawberry leaves and those affected by leaf scorch. Each class contains a large number of labeled images for training and evaluation purposes.

- **Source**: [PlantVillage Kaggle Dataset](link_to_dataset)
- **Number of Classes**: 2
- **Total Images**: 1565

## Model Architecture

The deep learning model used for this project is a convolutional neural network (CNN) with 6 convolutional layers. It is trained on the PlantVillage dataset to classify strawberry plant images into various disease categories.

## Usage

To train the model:
1. Download the PlantVillage dataset from the provided link.
2. Preprocess the data and keep only the "Strawberry___healthy" and "Strawberry___Leaf_scorch" classes, deleting all other plant classes and their images.
3. Split the dataset into training, validation, and test sets.
4. Train the model using the provided script or Jupyter Notebook.

To use the trained model for inference:
1. Load the trained model weights.
2. Preprocess the input image.
3. Feed the preprocessed image into the model for prediction.

## Dependencies

- Python 3.x
- TensorFlow 2.x
- Other dependencies (listed in requirements.txt)

## Author

Rituja

## License

[Include license information if applicable]
