# Deep Transfer Learning and XAI

This project explores the application of deep transfer learning for image classification and uses explainable AI (XAI) techniques to understand the model's decisions.

## Project Overview

The project consists of the following main components:

- **Transfer Learning:** A pre-trained model is fine-tuned for a new image classification task.
- **XAI Analysis:** Techniques are applied to visualize and interpret the model's predictions.
- **Dataset:** The project uses the WikiArt dataset, a large collection of images of artworks.

## File Structure

- `Assignment_4a.ipynb`, `Assignment_4b.ipynb`: Jupyter notebooks containing the main code for the project.
- `accuracyFC1.png`, `lossFC1.png`, `accuracyFC2.png`, `lossFC2.png`: Plots showing the accuracy and loss of the trained models.
- `images/`: Contains sample images for testing the model.
- `Utilities/`: Contains scripts for downloading and handling the WikiArt dataset.
- `imagenet_class_index.json`: A file containing the class names for the ImageNet dataset.

## Setup and Usage

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: A `requirements.txt` file is not provided. You will need to create one based on the imports in the Jupyter notebooks.)*

3. **Download the dataset:**
   The `Utilities/` directory contains scripts to download the WikiArt dataset.

4. **Run the notebooks:**
   Open and run the Jupyter notebooks `Assignment_4a.ipynb` and `Assignment_4b.ipynb` to train the models and perform the XAI analysis.

## Results

The training and validation accuracy and loss are shown in the following plots:

- `accuracyFC1.png`
- `lossFC1.png`
- `accuracyFC2.png`
- `lossFC2.png`

## Dataset

This project uses the WikiArt dataset. The scripts in the `Utilities/` directory can be used to download and prepare the dataset.
