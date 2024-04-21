# Project3-DS-4002
Welcome to our Project 3 info on Classifying Celebrity Faces as Young!

## Contents of our repository:
> Section 1: Software and platforms

> Section 2: Map of documentation

> Section 3: Instructions for reproducibility

## Section 1: Software and platforms
* Software
  * Visual Studio Code
* Packages needing installation
  * torch, torch.nn
  * numpy
  * Image from IPython.display
  * matplotlib.pyplot
  * torchvision
* Platforms
  * Windows
  * Mac
 
## Section 2: Map of documentation
* Project3-DS-4002
  * README.md
      * Orientation of repository
  * LICENSE.md
      * Terms and conditions
  * SCRIPTS
      * processing.ipynb
  * DATA
      * how to get the data.ipynb
  * OUTPUT
      * accuracy_higherLR.png
      * accuracy_increase_batch_size.png
      * accuracy_increasevalidation.png
      * accuracy_og.png
      * accuracy_var2.png
      * image_pred_og.png
      * image_pred_var2.png
  * REFERENCES
      * [1] “CelebA Dataset.” Available: https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html. [Accessed: Apr. 04, 2024]

      * [2] T. Gautam, “Create Your Own Image Classification Model Using Python and Keras,” Analytics Vidhya, Oct. 16, 2020. Available: https://www.analyticsvidhya.com/blog/2020/10/create-image-classification-model-python-keras/. [Accessed: Apr. 04, 2024]
   
## Section 3: Instructions for Reproducibility
1. Collecting Data: Refer to the **how to get the data.ipynb** file within the **DATA** folder. Download the data into the folder holding the **PROJECT3-DS-4002** cloned repository, and follow the file structure outlined in **how to get the data.ipynb**.
2. Model Preparation: To remove bias, you must randomly crop, flip, and adjust each image so that image attributes are not used in the classification, instead it is the actual features of the person in the image. Run the first 7 code blocks in the **processing.ipynb** file within the **SCRIPTS** folder to make these adjustments. Then, run the next code blocks in **processing.ipynb** to split the data into test, train, and validation groups.
3. Model Production: Run code blocks 9-15 within the **processing.ipynb** file to create and fine tune the model features.
4. Model Running: Run the rest of the **processing.ipynb** file to output and visualize the accuracy of the model predictions.
