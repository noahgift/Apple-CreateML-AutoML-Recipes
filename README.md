# Apple-CreateML-AutoML-Recipes

This is part of the book [Practical MLOps](https://learning.oreilly.com/library/view/practical-mlops/9781098103002/)

Some recipes around Apple CreateML

![image](https://user-images.githubusercontent.com/58792/115453563-c89d3880-a1ed-11eb-9a94-1fb1431203ac.png)


## To get started with CreateML

1.  Download [XCode](https://developer.apple.com/xcode/)
2.  Open up XCode and Right click on icon to launch CreateML

![CreateML](https://user-images.githubusercontent.com/58792/116000086-ca377980-a5bc-11eb-8842-11f2c862ca8e.png)

3.  Use Image Classifier template

![image-classification](https://user-images.githubusercontent.com/58792/116000191-2ac6b680-a5bd-11eb-800b-e264727d5bc8.png)


4.  Drop cats-dogs-small onto project and test-cats-dogs onto test

![upload-data](https://user-images.githubusercontent.com/58792/116000271-8133f500-a5bd-11eb-9825-b9e760956d63.png)


5.  Train the model

![trained-model](https://user-images.githubusercontent.com/58792/116000720-58acfa80-a5bf-11eb-99b2-825cece7bf74.png)

6.  Test it out by finding internet pictures of cats and dogs

![predict](https://user-images.githubusercontent.com/58792/116000743-6e222480-a5bf-11eb-9990-b420c04d9a73.png)

7.  Download model and use it in iOS application or convert it to another format.  

![create-ml-model](https://user-images.githubusercontent.com/58792/116000976-5dbe7980-a5c0-11eb-80f0-e29abbd73898.png)

Here is an example of the an `mlmodel` file:  https://github.com/noahgift/Apple-CreateML-AutoML-Recipes/blob/main/cats-dogs.mlmodel?raw=true

Next steps:

* You could train a more complex model by downloading a larger Kaggle dataset:  https://www.microsoft.com/en-us/download/details.aspx?id=54765
* You could try other types of AutoML

### Download and Convert a pre-trained model

* Follow this notebook:  https://github.com/noahgift/Apple-CreateML-AutoML-Recipes/blob/main/CreateML_Conversion.ipynb
* Download the model after converting

![download-colab](https://user-images.githubusercontent.com/58792/116013113-616ff180-a5fc-11eb-86f4-51d9a023f849.png)

* Open model in XCode and predict

![stingray-predict](https://user-images.githubusercontent.com/58792/116012566-3637d300-a5f9-11eb-86f6-ef8914829a3a.png)

### Video Walkthrough


[Create ML Walkthrough on the O'Reilly platform](https://learning.oreilly.com/videos/automl-with-apple/60424VIDEOPAIML/60424VIDEOPAIML-c1_s0)

![Create ML](https://user-images.githubusercontent.com/58792/116000644-1f748a80-a5bf-11eb-937f-93ff3078aa17.jpg)
