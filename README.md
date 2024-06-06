# Project 4 Image-Classification

### Steps taken to analyze the data:
Some steps I took to ensure I had a balanced dataset was to flip my drone images 90 degrees and 180 degrees. I didn't want to cut my bird images down to the amount of images my drone dataset had because that was over half of my bird data gone. I then resized all the images to 128*128 as not all the images were the same size, and I wanted to make it more consistent. During the analysis step, I merged both datasets and then did a train/test split on the data and flattened the images into a 1D array. After that, I normalized the train and test data, and then I put the training set data into the neural network. After that, I could run my test data to determine the accuracy of the image classification algorithm. 

The accuracy of my model was around 70% which could be because there was not enough data. If I had gotten a larger dataset, the model would have been more accurate when running the test data.
