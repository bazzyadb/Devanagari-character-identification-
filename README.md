# Devanagari character identification

This repository is an attempt to build a devanagari character classifier system. The input image is a 32*32 Devanagari character image and the output is a prediction of the character. 
The classifier is a CNN model built with the help of optimization techniques like Adam optimizer, Batch Normalization.

The script is runnable on google colab, for other platforms you will need to download this dataset: (https://www.kaggle.com/rishianand/devanagari-character-set)

There are 46 different labels considered and the labels are:

# क ख ग घ ङ च छ ज झ ञ ट ठ ड ढ ण त थ द ध न प फ ब भ म य र ल व श ष स ह chhya tra gya ० १ २ ३ ४ ५ ६ ७ ८ ९

To get kaggle.json file:
1. Go to your account, Scroll to API section and Click Expire API Token to remove previous tokens
2. Click on Create New API Token - It will download kaggle.json file on your machine
