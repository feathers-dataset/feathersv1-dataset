# FeathersV1 Dataset

> Dataset for feathers classification

The FeathersV1 Dataset contains 28,272 feather images of the web-nature. The images are collected from feather forums, public websites, and search engines.

Dataset is organized in simplified taxonomic order consisting of two layers, namely Order and Species.

Each image contains cropped image of single feather of bird, sometimes with part of adjacent feathers of the same species.

## Usage

This repository contains the following folders:

* data - contains the classes of images files in CSV format;
* images - contains image data in JPG format, split by subdirectories of Order and Species.

CSV files contains rows of the `filename`, `order` and `species` for each image. All data was split into `train_classes.csv` and `test_classes.csv` with proportions 80/20 on shuffled data.

## Licenses

**Disclaimer: all dataset images were taken from Internet open collections and public or private collections with the consent of the authors. Please check [AUTHORS](https://github.com/feathers-dataset/feathersv1-dataset/blob/master/AUTHORS) file for complete information about licenses and authors.**

In addition please refer to the FeathersV1 Dataset [**LICENSE**](https://github.com/feathers-dataset/feathersv1-dataset/blob/master/LICENSE) file.
