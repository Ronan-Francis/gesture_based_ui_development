# Gesture Based UI Development

## Week 1
The objective of this lab is to gain hands-on experience with building machine learning models using scikit-learn, also
known as sklearn. We will be building Linear Regression Models of some form throughout, and we will be assessing
them too.
Assessment and interpreting results is just as, if not more, important than building the models. Having an under-standing how each different type of model works will allow us to better interpret the results, evaluate the model and
maybe improve the model in the future.

--- 

## Week 2
This lab explored **train-test split**, **cross-validation**, and **polynomial regression** for model evaluation.  

- A **linear regression model** was trained on a single feature (`wt` for `mtcars`, `bmi` for `Diabetes`).  
- **Train-test split** (80/20) was used to compare training and testing scores.  
- **Cross-validation** helped assess model reliability across different data splits.  
- **Polynomial regression (degree=2)** was tested to improve predictions.  

---

## Week 4

This lab explores the application of logistic regression to classify colors using a dataset named `colour-data.csv`, which contains approximately 4000 data points. The task is to predict color labels based on RGB color values, leveraging logistic regression for multi-class classification.

The color labels include categories like red, orange, yellow, green, blue, purple, brown, pink, black, grey, and white. Each label is associated with representative RGB values for visualization purposes. The model uses LAB color space transformations to improve classification accuracy and enhance visual interpretability.

Key steps in the lab include:

1. **Data Preparation:**  
   The dataset is imported and analyzed to understand the distribution of colors.

2. **Color Space Transformation:**  
   RGB values are converted into LAB color space using `skimage.color.lab2rgb` to facilitate a more perceptually uniform representation.

3. **Model Training with Logistic Regression:**  
   Logistic regression is implemented using scikit-learn to predict color labels. The model is trained on the provided dataset and optimized to improve prediction accuracy.

4. **Visualization of Predictions:**  
   A custom `plot_predictions` function is employed to visualize model predictions across a grid of LAB color values at different luminance levels. This visualization helps evaluate how accurately the model distinguishes colors.

5. **Model Evaluation:**  
   Predictions are compared to ground truth labels to assess performance, identify potential misclassifications, and adjust model parameters if necessary.

---

## Week 5
