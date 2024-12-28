# PF_On_MNIST

## Project Description
This project presents an innovative approach for creating robust and compact Professional Forest (PF) models that achieve world-class performance on the MNIST dataset by combining Convolutional Neural Networks (CNN) and PF methodologies. The goal is to demonstrate how we can build efficient, scalable, and high-performing models with fewer trees, making them suitable for applications such as IoT devices.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
  - [Data Loading and Preprocessing](#data-loading-and-preprocessing)
  - [CNN Model](#cnn-model)
  - [Random Forest Model](#random-forest-model)
  - [Primary Forest (PF) Model](#primary-forest-pf-model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation
To run this project, you need to have Python and the following libraries installed:
- TensorFlow
- NumPy
- Scikit-learn

Install the required libraries using:
```bash
pip install tensorflow numpy scikit-learn
Usage
Clone the repository:

bash
git clone https://github.com/your-username/Professional_Forest_Projects.git
Navigate to the project directory:

bash
cd Professional_Forest_Projects/PF_On_MNIST
Run the Jupyter notebook:

bash
jupyter notebook your-notebook.ipynb
Project Structure
PF_On_MNIST/README.md: Project documentation and instructions.

PF_On_MNIST/LICENSE: MIT License for the project.

PF_On_MNIST/your-notebook.ipynb: Main Jupyter notebook containing the code and analysis.

PF_On_MNIST/data/: Directory for storing dataset files (if applicable).

PF_On_MNIST/performance_metrics.xlsx: Excel file comparing the performance metrics of different models.

Methodology
Data Loading and Preprocessing
Load the MNIST dataset containing handwritten digit images.

Preprocess the images by normalizing the pixel values to [0, 1] and reshaping them to include a channel dimension.

CNN Model
Build a Convolutional Neural Network (CNN) using the LeNet-5 architecture.

Train the CNN on the MNIST dataset to extract features from the penultimate layer.

Random Forest Model
Train a Random Forest model using the extracted features from the CNN.

Optimize the Random Forest model using RandomizedSearchCV to find the best hyperparameters.

Primary Forest (PF) Model
Create a Primary Forest with 2000 trees and train it on the extracted features.

Select the top 100 trees based on individual performance scores.

Create and evaluate the PF model using these top 100 trees.

Explore the performance of PF models with 75, 50, 25, 10, and 5 trees.

Results
Our results demonstrate the effectiveness of combining CNNs with ensemble methods:

CNN + RF (100 Trees):

Accuracy: 99.05%

Precision: 99.04%

Recall: 99.03%

F1 Score: 99.094%

CNN + RF + RandomizedSearchCV:

Accuracy: 99.01%

Precision: 99.00%

Recall: 98..99%

F1 Score: 98.99%

CNN + PF (100 Professional Trees):

Primary Forest (2000 trees) Accuracy: 99.07%

PF Model (100 Trees) Accuracy: 99.05%

Precision: 99.04%

Recall: 99.03%

F1 Score: 99.04%

CNN + PF (75 Trees):

Accuracy: 99.03%

Precision: 99.02%

Recall: 99.01%

F1 Score: 99.02%

CNN + PF (50 Trees):

Accuracy: 99.05%

Precision: 99.04%

Recall: 99.03%

F1 Score: 99.04%

CNN + PF (25 Trees):

Accuracy: 99.04%

Precision: 99.03%

Recall: 99.02%

F1 Score: 99.03%

CNN + PF (10 Trees):

Accuracy: 99.02%

Precision: 99.00%

Recall: 99.01%

F1 Score: 99.01%

CNN + PF (5 Trees):

Accuracy: 99.00%

Precision: 98.99%

Recall: 98.99%

F1 Score: 98.99%

Highest RF on MNIST:

Accuracy: 96-97%

Precision: N/A

Recall: N/A

F1 Score: N/A

These results show that our approach is robust and competitive, achieving near world-class performance with fewer trees, making it efficient, scalable, and robust.

Additionally, it is noteworthy that the performance of the PF model with only 5 trees is better than that of the Random Forest model with 100 trees. This is very important as it showcases the powerful capability of the PF methodology to create a very tiny and scalable model, making it ideal for traditional usages such as IoT applications.

It’s important to note that we can achieve even higher performance by utilizing more advanced CNN models. Considering that the Test Accuracy of the LeNet-5 CNN model is 99.03%, we used this accuracy as a basis to feed into our RF and PF models. By employing better CNN architectures, there is potential to further enhance the overall performance of the combined models.

Overall, these findings indicate that the CNN + PF approach is robust, scalable, and competitive, achieving near world-class performance with a significantly reduced number of trees. This makes it an excellent choice for real-world applications where computational efficiency and resource utilization are critical.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions or inquiries, please contact:

Ali M Shafiei: your-email@example.com


