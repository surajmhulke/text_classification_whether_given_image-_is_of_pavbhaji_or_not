# text_classification_whether_given_image-_is_of_pavbhaji_or_not
The goal here is to train a model that can text classify whether a given image is of pavbhaji or not

NOTE :

This is text based classification challenge and not CNN computer vision based challenge.
Json file contains metadata for instageram post is to be used for classification
Images are provided for the instagram post in the json_meta.
GIVEN :
The data dir consists of data that have #pavbhaji in their description or comment.

dataset.zip
    |
 dataset
     |--- images
             |--- 1 (pavbhaji images)
             |--- 0 (non-pavbhaji images)
     |--- pavbhaji.json (post meta data)
Where json file consist of entries for post and its metadata.

TASK:
List down features and their relevance for training a classification model.
Train the model & predict whether the image contains the Pav-Bhaji or not.
