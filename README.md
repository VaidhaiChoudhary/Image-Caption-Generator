# Image-Caption-Generator
Image caption generator is a project that involves computer vision and natural language processing concepts to recognize the context of an image and describe them in a 
natural language like English. For implementing the project, techniques used are CNN with LSTM.

The image features will be extracted using a CNN model trained on the imagenet dataset and then we feed the features into the LSTM model which will be responsible for 
generating the image captions.

Flickr_8K : Flicker8k_Dataset  – Dataset folder which contains 8091 images.
            Flickr_8k_text  – Dataset folder which contains text files and captions of images.
            link to download dataset- https://paperswithcode.com/task/image-captioning 
            
Steps for Project:
1. Importing all the necessary packages.
2. Getting and performing data cleaning.
3. Extracting the feature vector from all images.
4. Loading dataset for Training the model.
5. Tokenizing the vocabulary.
6. Creating a data generator.
7. Defining the CNN-RNN model.
8. Training the model.
9. Testing the model.            
