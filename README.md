# Artificial Neural Networks and Deep Learning HW1 - AY 2023/2024

## Challenge: Image Classification

<p align="center">
	<img src="images/head-image.png" height="250" />
</p>

This challenge's goal was to train a classifier to correctly predict whether an image represented a **healthy** or **unhealthy** plant.

We examined three distinct approaches to address the task at hand:

1. Custom CNNs
2. Utilizing Transfer Learning and Fine-Tuning with pre-trained models sourced from the [Keras Applications](https://keras.io/api/applications/) on the ImageNet dataset.
3. Implementing Self-Supervised Learning techniques and Ensemble models.

After thorough evaluation, the combination of **Transfer Learning + Fine-Tuning** emerged as the most effective strategy for solving this challenge.

## Data Analysis and Augmentation

The original dataset contained X outliers, which we identified and removed to ensure the quality of our training data. Following data preprocessing, data augmentation played a pivotal role in enhancing the robustness of our models. We utilized a variety of augmentation techniques sourced from KerasCV's official APIs, including:

- Random Flips
- Random Translations
- Random Rotations
- Random Zoom
- Random Brightness
- Random Crop
- CutMix/Mixup
- GaussianNoise
- RandAugment

## More Information

For a detailed overview of the challenge, methods, and models built, please refer to the [report](/docs/Report_Challenge_1.pdf) and the [notebooks](/notebooks/Challenge%201/).

### Results

Our best model achieved a test-set accuracy of **0.88** on the private test set, positioning our team in the **top 10%** among over 580 participants.

## Team
* [Jacopo Piazzalunga](https://github.com/Jacopopiazza)
* [Davide Salonico](https://github.com/DavideSalonico)
* [Gabriele Puglisi](https://github.com/GabP404)
* [Denis Sanduleanu](https://github.com/#)

