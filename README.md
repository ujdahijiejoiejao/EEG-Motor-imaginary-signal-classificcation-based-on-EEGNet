# EEG-Motor-imaginary-signal-classificcation-based-on-EEGNet
The final project of Mingyang Gao (mg7170) in deep learning course.

The final_project.ipynb is the main code of the project. The documents in Data folder is the bci-iv-2a dataset for each volunteer. Only A01T, A03T, A09T is used in this project. The result folder is the result accuracy of the training. The code in the notebook will load those data. Because I did the project in the colab notebook environment, the path of the files in the notebook isn't correct, so the path should be changed to the correct path to run the code.

The main code notebook has 3 parts, the first is the import of data, it uses the mne library to import and do some preprocessing to the data. The 'filename' in the second cell should be changed to run the code.

The second part is the training process. The result of training will be saved under the same folder as the final_project.ipynb.

The third part is the result part. The plot of loss and accuracy will be drawn by the matplotlib. If run the second part and saved the result already, you can just run the code. If use my result, you should change the path of the documents.
