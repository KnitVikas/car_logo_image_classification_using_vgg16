# car_logo_image_classification_using_vgg16

The model is about classifying the images of logos of cars. There are five class of logo of images are labeled as audi,bmw,chevrolet,
jaguar,mercedes etc.

I have used the pretrained vgg16  model to classify these images the pretrainded model of keras could be downloaded from here :
https://github.com/fchollet/deep-learning-models.

DATA:
the model has been trained on the 279 datasets only. which i have uploaded in train1.zip folder. you can use your own
data to train.Under test_images_model1 i have uploaded the images on which i test the models and it gives me correct
prediction on these images.you use your own images to test this model.
 
ACCURACY & TRAINING:
the model i.e custom VGG10 model gives arrount 85 percent accuracy on the data.
while after fine tuning the model it gives around 91 percent of accuracy which is much
better for such a small data set.
 
TESTING & SAVING MODEL:
I have test the model on many images and it gives me accuracy on almost every images.You can test your on images to test it.
at last i have shown that how to save our model for further testing the images without training it again.
