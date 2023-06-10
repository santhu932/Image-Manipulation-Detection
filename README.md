# CV-Project

| Model      | 1000 Train | 1000 Test | 1000 F1 | 5000 Train | 5000 Test | 5000 F1 | 10000 Train | 10000 Test | 10000 F1 | 
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |----------- | 
| ResNet50     | 0.88 | 0.64 | 0.61 | 0.88 | 0.72 | 0.71 | 0.93 | 0.88 | 0.87 |
| VisionTransformer  | 0.91 | 0.68 | 0.60| 0.92 | 0.81| 0.79 | 0.94 | 0.90 | 0.87 |
| InceptionV3 | 0.90 | 0.71 | 0.65 | 0.88 | 0.75 | 0.67 | 0.92 | 0.89 | 0.88 |
| GoogLeNet | 0.91 | 0.68 | 0.68 | 0.77 | 0.71 | 0.72 | 0.85 | 0.83 | 0.82 |
| DenseNet | 0.98 | 0.67 | 0.64 | 0.93 | 0.72 | 0.70 | 0.89 | 0.84 | 0.82 |
| ResNeXt50 | 0.99 | 0.62 |0.61 | 0.97 | 0.76 | 0.72 | 0.94 | 0.89 | 0.88 |
| ELA + ResNeXT (Ours) | 0.92 | 0.75 | 0.69 | 0.93 | 0.83 | 0.82 | 0.98 | 0.94 | 0.93 |


Results for the models: ResNet50, Vision Transformer, InceptionV3, GoogLeNet, DenseNet, ResNeXt50. Run all the blocks of "classifier.ipynb" notebook for train and test accuracy.

Results for the model "ELA + ResNeXT": Run the "data.ipynb" notebook first to preprocess the raw RGB images to generate corresponding error level analysis of the image. Then run all the blocks of "ELA_ResNeXt_Classifier.ipynb" for train and test accuracy.

Run the "plots.ipynb" notebook for Train Accuracy plot and confusion matrix of the best performing model.


<img src="https://github.iu.edu/jbhendri/CV-Project/blob/0ac1074c41042cb1e92d995a878738d375eb58f2/plot.png" width="400" height="300"> <img src="https://github.iu.edu/jbhendri/CV-Project/blob/0ac1074c41042cb1e92d995a878738d375eb58f2/Confusion%20Matrix.png" width="400" height="300">

# Project Poster:

<img src="https://github.iu.edu/jbhendri/CV-Project/blob/0ac1074c41042cb1e92d995a878738d375eb58f2/CV_Posterpdf.png" width="900" height="700">
