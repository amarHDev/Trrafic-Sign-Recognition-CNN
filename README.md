# German Traffic Sign Recognition Benchmark (GTSRB)
This project aims to recognize traffic signs from the German Traffic Sign Recognition Benchmark (GTSRB) dataset, which contains 43 classes of traffic signs. The dataset includes more than 50,000 images in total, split into 39,209 training images and 12,631 test images.

# Dataset

The GTSRB dataset is a challenging dataset due to the varying light conditions and rich backgrounds present in the images. The images are 32x32 pixels in size and are RGB.

# Requirements

- Python 3.x
- Pytorch
- Matplotlib
- Pandas

# Usage

1- Clone the repository 'git clone https://github.com/amarHDev/Trrafic-Sign-Recognition-CNN.git'

2- Install the required packages: 'pip install -r requirements.txt'

3- Download the GTSRB dataset from the official website (https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) and extract it to the project directory.

4- Run the jupyer file : preprocessing.ipynb for preprocessing data

5- Run the jupyer file : Our-CNN-Model.ipynb

# Results

The model's performance will be evaluated using accuracy on the test dataset. This model can be improved by fine-tuning the hyperparameters and adding data augmentation to the dataset.

# References

The GTSRB dataset can be found on the website (https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

The paper "The German Traffic Sign Recognition Benchmark: A multi-class classification competition" (Stallkamp, J., Schlipsing, M., Salmen, J., and Igel, C.) can be found on the official website (http://benchmark.ini.rub.de/?section=gtsrb&subsection=news)
