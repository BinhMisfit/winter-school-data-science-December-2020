# How to run our codes:
1. First, please download all data and Colab notebook and put them into your Google Drive:
2. Use the following python codes to define the current working directory:

import os

from google.colab import drive

drive.mount('/content/gdrive')

my_drive = '/content/gdrive/MyDrive'

path = os.path.join(my_drive, "AISIA/Paper submission recommendation")

data_dir = os.path.join(path, "")

3. Run the Google Colab Notebook provided.

