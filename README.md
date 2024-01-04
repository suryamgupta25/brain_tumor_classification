# brain_tumor_classification

This project is a manually-trained machine learning model that classifies MRI images of brain tumors into four categories: glioma, meningioma, pituitary, and no tumor.

The dataset is linked here: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data

Out of the 7023 images in the dataset, 5712 (81%) are dedicated to training and 1311 (19%) are dedicated to testing.

Portion of dataset for each image classification:
- Glioma: 1621 images (1321 training, 300 testing)
- Meningioma: 1645 images (1339 training, 306 testing)
- Pituitary: 1757 images (1457 training, 300 testing)
- No tumor: 2000 images (1595 training, 405 testing)
As there is a relatively equal amount of data for each classification, this dataset was an ideal option.


Model train time: 8 minutes, 31 seconds (2 CNN layers, 4 Linear layers)

Number of parameters: 53,031,092

Training accuracy: 99.26%

Testing accuracy: 95.80%
