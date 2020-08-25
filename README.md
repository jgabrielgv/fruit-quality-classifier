# fruit-quality-classifier

## Project description

This classifier predicts if a fruit is a banana or an orange, using a pre-trained keras model created using Teachable Machine. Then, it uses OpenCV to extract three different shapes: green, orange and red and then resolves the fruit type based off the percentage of each color in the fruit (this last step using [fruit_cv.py](https://github.com/ArjunKini/Fruit-Freshness-Detection/blob/master/fruit_cv.py) as the base algorithm).

## Steps to run the app on Google Collab

* Upload notebooks/fruit_quality_detector.ipynb to Google Collab
* Clone the repo (# Step 1)
* Load the model (# Step 2)
* Load the ripeness predictor (# Step 3)
* Run the predictor (# Step 4)

## Links to repos

Link to fruit quality classifier repo: [fruit-quality-classifier](https://github.com/jgabrielgv/fruit-quality-classifier)

Link to dataset repo: [fruit-images-dataset](https://github.com/jgabrielgv/fruit-images-dataset)
