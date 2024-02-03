Project: Image to Image Translation using conditional GANs

Overview
This project focuses on image-to-image translation using Conditional Generative Adversarial Networks (cGANs) and is designed for facade generation. The model is trained to smoothly translate architectural sketches into realistic and colorful illustrations, with potential applications in artistic endeavors, urban planning, and architectural design.

Dataset
The dataset used for training and validation can be downloaded from this link: https://efrosgans.eecs.berkeley.edu/pix2pix/datasets/. After downloading, upload the dataset to your Google Drive.

Trained Model Link: https://drive.google.com/drive/folders/1YAAragfNsjH5TRGGechVPk63oF8cvg6k?usp=sharing

Presentation Zoom Video Link: https://rit.zoom.us/rec/share/4GjgfRwqaKBtheAw44BQAzwtUk4wPzL-7io2bbqwhQyIZTUji1PLfifcT3Y7Mr7_.OL_kWn8urSBoVkV9 

Prerequisites:
1. pytorch, torchvision should be already installed on the system.
2. The program requires Nvidia GPU processor.

Steps to Reproduce

Step 1: Download and Upload Dataset
Download the dataset from the provided link.
Upload the dataset to your Google Drive.

Step 2: Update Hyperparameters in cGan_train.ipynb
Adjust hyperparameters in the code to suit your requirements. Important hyperparameters include image dimensions, batch size, learning rates.

Step 3: Train the Model
Execute the training program to train the cGAN model. This will generate a trained model file.

Step 4: Validate with Validator Program (cGAN_validate.ipynb)
Execute the validation program to assess the model's performance on new images.

Results
The trained model can generate high-quality facades from input sketches, demonstrating the effectiveness of the cGAN architecture in capturing complex patterns.
Due to resource constraints, we were not able to train for more than 500 epochs.
