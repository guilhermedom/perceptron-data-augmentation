# Perceptron Classification With Data Augmentation

A showcase of how image data augmentation can be used with a Perceptron classifier.

---

## Problem Overview

Although being a simple classifier, a perceptron can still be used to get nice results processing images. Even in common scenarios where there is little data available having the desired quality, data augmentation can be applied to improve a perceptron's performance.

In this showcase, we use a pair of images to train a perceptron model to perform binary classification:

![182ce94c-ed58-4f52-824e-74f97d4d8461](https://user-images.githubusercontent.com/33037020/187822384-e6e352ce-015a-4c92-b9c5-6e6a56c41384.png)

## Analysis Introduction

As there are just these 2 sample images, we generate others using pepper and rotation effects until we can create a small dataset. Below it is possible to see a couple of generated images:

![8adf2e53-b666-4157-b3e5-d30b59618845](https://user-images.githubusercontent.com/33037020/187822473-91636d17-6e88-4524-ba2e-36185c65d7c8.png)

The model's accuracy is measured at 100% for both train and test sets. With this we show that perceptrons can be handily used in simple image recognition tasks.

Lastly, we evaluate the model's confidence when classifying poor quality samples. These samples come from handwritten symbols that are similar to the ones in the training images:

![query0](https://user-images.githubusercontent.com/33037020/187822685-60754cb5-81b3-4101-9519-f58695e00940.png)
![query2](https://user-images.githubusercontent.com/33037020/187822698-a12dc0fb-bace-469b-8c97-dad48e4ee701.png)

We are able to show that perceptrons can deal with poor quality, or poorly written symbols, classifying them correctly, but with some difficulty.

[//]: #


