# Deep_Learning_image_class_fish
Image classifier for different type of fish
https://colab.research.google.com/drive/12Pjgm3ncP3M97W6aTVR9DkF-PamM00Yk?usp=sharing

Image Classifier for fish
The project consists of classifying different types of fish images. The different types of fish are Black Sea Sprat, Gilt-Head Bream and Shrimp.
Data

Black Sea Sprat
![00001](https://user-images.githubusercontent.com/40518603/113001529-82286100-918e-11eb-97c5-47868e92731c.png)

 

Gilt-Head Bream
![00001](https://user-images.githubusercontent.com/40518603/113001484-79378f80-918e-11eb-87b1-eeb0f689db6d.png)

 

Shrimp
![00001](https://user-images.githubusercontent.com/40518603/113001353-5c9b5780-918e-11eb-9f4c-2ebfc5682c77.png)


 
Workflow
Data Collection
The images are collected from encyclopedia.
Data Preprocessing
•	We resize images by the size given by IMAGE_SIZE = [224, 224].

Model Creation
•	We use imagenet  dataset and we use transfer training of InceptionV3 to save computational time.
•	We use Softmax as activation function for the output layer
•	We do it for multiclass classification the output.
•	We find the accuracy.

