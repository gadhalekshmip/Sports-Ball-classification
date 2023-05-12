# Sports-Ball-classification

This project implements a Convolutional Neural Network (CNN) using PyTorch for ball detection. It focuses on detecting the following ball categories:'american_football', 'baseball', 'basketball', 'billiard_ball', 'bowling_ball', 'cricket_ball', 'football', 'golf_ball', 'hockey_ball', 'hockey_puck', 'rugby_ball', 'shuttlecock', 'table_tennis_ball', 'tennis_ball', 'volleyball' . The CNN model is trained on a labeled dataset of images from these categories to learn the distinguishing features of each scene type.

Installation
To run this project, you need to have Python and PyTorch installed on your system.
Additionally, you need to install the following packages:

- Python 3.7 or higher
- PyTorch
- torchvision
- NumPy
- Matplotlib
You can install PyTorch and torchvision based on your system configuration by visiting the official PyTorch website (https://pytorch.org/get-started/).

Usage
To use this scene detection project, follow these steps:

- Prepare your dataset with labeled images for each scene category: 'buildings', 'forest', 'glacier', 'mountain', 'sea', and 'street'.
- Update the cnn_training.ipynb file with the path to your dataset and any desired configurations or settings.
- Run the cnn_training.ipynb file 
- The program will load the CNN model, train it on your dataset, and display the training progress.
- After training, the program will evaluate the model's performance on a test dataset and display the accuracy.
- You can then use the trained model to predict the scene category for new input images by calling the appropriate functions.
Note: Ensure that your dataset is properly organized and labeled with images corresponding to the scene categories mentioned above.

Customization
You can customize the CNN model and training process by modifying the code. For example, you can change the architecture of the CNN, adjust hyperparameters such as learning rate and batch size, or apply data augmentation techniques to improve performance.

