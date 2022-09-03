# Brain-Tumor-Detection-Transfer-Learning-and-Fine-Tuning
Transfer learning & fine-tuning for brain tumor detection from brain MRI Images

* Fine-tuning a binary image classification model for detecting brain tumor.
* The dataset consists of 253 brain MRI images.
* Each example is a 256 x 256 x 3 RGB image.
* The InceptionV3 architecture is used as base CNN model for transfer learning.
* Prefetching and multithreaded loading & preprocessing are implemented to improve speed.
* A dropout layer and data augmentation are implemented for strong regularization. 
* The last 40 layers of the base model, InceptionV3, are unfreezed for fine-tuning.
* Accuracy of 92% is achieved on validation and test datasets.

* Source: https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection
