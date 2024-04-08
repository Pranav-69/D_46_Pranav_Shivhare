# Description:
The Dangerous Farm Insects Image Dataset is a curated collection of images featuring 3 different types of insects commonly found in agricultural settings. This dataset provides valuable visual resources for studying, identifying, and understanding the characteristics of these potentially harmful insects. Each insect is represented by multiple high-quality images, showcasing their distinct features, colors, and patterns.

## Dataset Link : https://www.kaggle.com/datasets/tarundalal/dangerous-insects-dataset/data

## Models
### 1. Convolutional Neural Network (CNN)
- CNN is a widely used deep learning architecture for image classification tasks.
- It consists of convolutional layers followed by pooling layers and fully connected layers.
- We have implemented a basic CNN architecture for this project.

### 2. ResNet
- ResNet (Residual Network) is a deep learning architecture that introduced the concept of residual learning.
- It allows training very deep neural networks effectively by using skip connections.
- We have used a pre-trained ResNet model for transfer learning in this project.

### 3. VGG19
- VGG19 is another deep learning architecture known for its simplicity and effectiveness.
- It consists of 19 layers with a combination of convolutional and pooling layers.
- We have used a pre-trained VGG19 model for transfer learning in this project.

## Usage
- The project involves classifying images of dangerous farm insects into different categories.
- We have used the mentioned models to build classifiers that can accurately identify these insects.
- Each model has been trained and evaluated using appropriate datasets.
- The choice of models was based on their performance in similar image classification tasks and their suitability for our dataset.

## How to Use
1. Clone the repository: `git clone https://github.com/yourusername/insect-classification.git`
2. Navigate to the project directory: `cd insect-classification`
3. Install the necessary dependencies: `pip install -r requirements.txt`
4. Run the model training script: `python train_model.py`
5. Test the trained models: `python test_model.py`

Feel free to explore and modify the code to suit your needs!
