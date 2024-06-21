# Machine Learning part of Fasimagiland

## Description

**Data:**
   - Utilizing the [Google QuickDraw!](https://console.cloud.google.com/storage/browser/quickdraw_dataset/sketchrnn?pageState=(%22StorageObjectListTable%22:(%22f%22:%22%255B%255D%22))&prefix=&forceOnObjectsSortingFiltering=false) dataset.
   - This [dataset](https://drive.google.com/drive/folders/1oQpS2LVKm1o1JNrXl10DW1ndwIbxf_kh?usp=sharing) contains 43 classes with a total of 258,000 data points.

**Augmentation:**
   - Performing data augmentation using various techniques such as:
     - Rotating
     - Shifting
     - Shearing
     - Zooming
     - Flipping

**Preprocess:**
   - Conducting data preprocessing with steps such as:
     - Reshaping
     - Normalizing
     - Compressing

**Model:**
   - Using the pre-trained ResNet50 model from TensorFlow.
   - Adding additional MLP (Multilayer Perceptron) classifiers.

**Loss and Optimizer:**
   - Using Cross Entropy Loss as the loss function.
   - Using Adam Optimizer as the optimizer.
