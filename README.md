# Image-Caption-Generator
**Image Caption Generator** is a project that involves computer vision and natural language processing concepts to recognize the context of an image and describe them in a natural language like English. For implementing the project, techniques used are CNN with LSTM.
The image features will be extracted using a CNN model trained on the imagenet dataset and then we feed the features into the LSTM model which will be responsible for 
generating the image captions.

**Flickr_8K** : 
Flicker8k_Dataset  – Dataset folder which contains 8091 images.
Flickr_8k_text  – Dataset folder which contains text files and captions of images.
link to download dataset- https://paperswithcode.com/task/image-captioning 
            
**Steps for Project:**
1. Importing all the necessary packages.
2. Getting and performing data cleaning.
3. Extracting the feature vector from all images.
4. Loading dataset for Training the model.
5. Tokenizing the vocabulary.
6. Creating a data generator.
7. Defining the CNN-RNN model.
8. Training the model.
9. Testing the model.            

**Output Images**


<img width="451" alt="output_ss_dog" src="https://user-images.githubusercontent.com/83226948/192143560-2d7ef83f-5dfd-492b-92ed-028ba074120e.png">
<img width="451" alt="output_ss_man in blue short in water" src="https://user-images.githubusercontent.com/83226948/192143588-faeea737-c05b-416e-aa48-c6d675b5f13e.png">
<img width="449" alt="output_ss_man in blue short jumping on water" src="https://user-images.githubusercontent.com/83226948/192143591-47d1527e-8284-4d61-a888-8512b8dc8e7e.png">
<img width="449" alt="output_ss_man in white shirt playing ball" src="https://user-images.githubusercontent.com/83226948/192143596-a51ea83b-f4e4-406d-9226-e7e85bb1407e.png">
<img width="451" alt="output_ss_man" src="https://user-images.githubusercontent.com/83226948/192143603-f8cd6d3c-2af7-45f2-bb0d-0da3174d543b.png">
