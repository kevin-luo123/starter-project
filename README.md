# starter-project

Introduction:
The goal for this project was to generate a dataset of 2d images and train a neural network to classify them. 

Dataset of Images:
To generate the images, I randomly set pixel values and pasted pixel values over to create a dataset of random images all with the same set of shapes. 

Neural Network: 
I experimented with several different common CNN architectures, tweaking them a bit to fit the dataset and labels I created. The model was trained over 10+10 epochs to achieve 100% accuracy on the test dataset. I experimented with many different layers and hyperparameters before landing on a functioning model. 

Discussion:
- I could try running the same project but with 3d images instead or with a larger 2d image. 
- For the current project, I could use more complex shapes, use more shapes so more labels need to be considered, or merge the shapes with the background image instead of simply overwriting the pixel values. 
- I could also use unsupervised learning to cluster the images and generate labels instead of providing them, and then try classifying the dataset using the CNN.  