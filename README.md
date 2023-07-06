# SWEusingDCGAN
This Steganography without Embedding techniqu uses DCGANs to hide secret data in the noise vector of a stego image to avoid detection by current steganalysis algorithms. An extractor is trained to estimate the noise vector from the stego image and obtain original secret data.

# Instructions
Since code was written in Google Colab, the code has been attached in the form of an ipynb file. 
For best experience, kindly open it in google colab.(Go to Colab->Open Notebook->Upload->Select ipynb file)
-------*-------*-------*-------*-------*-------*-------*-------*-------*-------*-------*-------*-------*-------*-------*-----
Once notebook has been opened, follow below steps:
1. For uploading dataset to runtime, first generate Kaggle API token and upload the kaggle.json file to runtime
   (refer to first 3 steps in this article: https://www.kaggle.com/general/74235)
2. Run all the code cells one after another.
3. In order to change number of epochs or any other hyperparameters, kindly refer to the hyperparameter code cell.

