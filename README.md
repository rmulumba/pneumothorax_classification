# Udacity Machine Learning Engineer Nanodegree 

## Capstone Project

Ronald Mulumba<br>

July 23, 2019

## Description
   
This is a capstone project for partial fulfillment of the Udacity Machine Learning Engineer Nanodegree program.<br>
The solution will aim to predict the existence of a pneumothorax in a test image using a convolutional neural network and indicate the extent of the condition using binary masks and encode them using run-length-encoded (RLE) masks.

## Data source
SIIM-ACR Pneumothorax Segmentation <br>
[Identify Pneumothorax disease in chest x-rays](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation/overview/description)

## Dependencies
- [Numpy](https://www.numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Pyplot](https://matplotlib.org/3.1.0/api/_as_gen/matplotlib.pyplot.html)
- [Pydicom](https://pydicom.github.io/pydicom/stable/getting_started.html)
- [TQDM](https://tqdm.github.io/)

## Reference
- [Pneumothorax](https://en.wikipedia.org/wiki/Pneumothorax)
- [DICOM Processing and Segmentation in Python](https://www.raddq.com/dicom-processing-segmentation-visualization-in-python)
- [Getting to know DICOM and the data](https://www.kaggle.com/schlerp/getting-to-know-dicom-and-the-data/data)
- [Mask-rcnn with augmentation and multiple masks](https://www.kaggle.com/abhishek/mask-rcnn-with-augmentation-and-multiple-masks#Convert-Model-to-Evaluation-Mode)
- [Intro - chest xray, DICOM, viz, U-nets - full data](https://www.kaggle.com/jesperdramsch/intro-chest-xray-dicom-viz-u-nets-full-data)
- [Full dataset](https://www.kaggle.com/seesee/full-dataset)
- [Finding Pneumo part 1 EDA and UNET](https://www.kaggle.com/ekhtiar/finding-pneumo-part-1-eda-and-unet)
- [Read DICOM and ploting using matplotlib](https://pydicom.github.io/pydicom/stable/auto_examples/input_output/plot_read_dicom.html)
- [Converting a dicom dataset to a standard python dictionary](https://github.com/pydicom/pydicom/issues/319)
- [Image Pre-processing for Chest X-ray](https://www.kaggle.com/seriousran/image-pre-processing-for-chest-x-ray)