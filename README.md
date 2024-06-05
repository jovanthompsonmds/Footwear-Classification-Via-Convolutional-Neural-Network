# Shoe, Sandal, and Boot Classification Using CNN  

## Overview  
This project leverages a Convolutional Neural Network (CNN) to classify images of shoes, sandals, and boots. Using a dataset of 15,000 images, the model achieved a test accuracy of 97.33%, showcasing the effectiveness of deep learning in image classification tasks.  

## Features  
- **Data Preprocessing**: Resizing, normalizing, and splitting the dataset for training and testing.  
- **CNN Architecture**: Four convolutional layers, each with pooling, followed by dense layers for classification.  
- **Performance Evaluation**: Validation accuracy, loss graphs, and optimizer comparisons.  
- **Optimizer Analysis**: Comparison of Adam, SGD, and RMSprop optimizers for model performance.  

## Files  
1. `Shoe_Sandal_Boot_Classification.ipynb`  
   - Code for data preprocessing, CNN model training, evaluation, and visualization.  
2. `shoe_sandal_boot_dataset/`  
   - Image dataset used for training and testing.  
3. `model_predictions.csv`  
   - Predicted classifications for test images.  

## Requirements  
- Python 3.8 or higher  
- Required libraries:  
  - `tensorflow`  
  - `numpy`  
  - `matplotlib`  
  - `scikit-learn`  
  - `opencv-python`  

Install dependencies using: 
pip install tensorflow numpy matplotlib scikit-learn opencv-python  
  
  

## Usage
1. Clone the repository and navigate to the project directory:
git clone https://github.com/jovanthompsonmds/Footwear-Classification-Via-Convolutional-Neural-Network.git

2. Run the Jupyter Notebook:
- Preprocess the images.
- Train the CNN model.
- Evaluate performance metrics and visualize results.

3. Analyze optimizer comparisons to determine the best configuration.

## Insights
The CNN model achieved a high test accuracy of 97.33%, with Adam optimizer showing the best performance. Loss and accuracy graphs indicated effective training. The project demonstrates deep learning's capability to handle complex image classification tasks with real-world applications.

## Contributing
Contributions are welcome! If you'd like to improve the project, add features, or provide feedback, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Developed by Jovan Thompson as part of a data science portfolio project.
