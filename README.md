# Overview

Detecting Pneumonia with Deep Learning and Convolutional Neural Networks

Shares common symptoms with other conditions
Tests to diagnose pneumonia are great but they take days for results
A doctor can misdiagnose pneumonia from an X-ray
Failure to notice inflammation
Irregular pattern
Human error

![png](docs/images/docter.png)

# Data Analysis

I have 5216 pneumonia and normal x-ray images

## X-ray Images

I can't compare with normal and pneumonia x-rays

Discovering patterns with your naked eye is hard
It’s inconsistent 
Unable to confidently replicate 
Conflicting diagnoses may occur

![png](docs/images/xrays.png)

## Normal X-ray

This is Normal X-ray

![png](docs/images/normal.png)

## Pneumonia X-ray

This is pneumonia X-ray

![png](docs/images/pneumonia.png)

# Preprocessing

I transfomed the images to tensor (150,150,3)

![png](docs/images/rgb.png)

# Train Model

## Model 1

I create first test model

![png](docs/images/model1.png)

## Model 2

I developed the model

![png](docs/images/model2.png)

# Conclusion

Our model is:

Thousands of times faster at predicting pneumonia than any doctor
3% more accurate than a doctor

More accessible than a doctor

Provides a mathematic approach to evaluating image data

Reading an X-ray is closer to getting blood work results with our model

notebook
![link](docs/notebook.pdf)

presentation
![link](docs/presentation.pdf)

github
![link](docs/github.pdf)
