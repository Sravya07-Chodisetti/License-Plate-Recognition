# License-Plate-Recognition


Tools required to install in your Local:
----------------------------------------
1. Pytesserract Installation:
-----------------------------

> https://github.com/UB-Mannheim/tesseract/wiki

step 1: Use the above link to download tesseract OCR for windows

step 2. Install this exe in C:\Program Files (x86)\Tesseract-OCR

step 3. Make sure you use the same path where tesseract is installed is used in the coding.

--------------
2. Jupyter Notebook
--------------------

your PC should contain Jupyter notebook.

> https://www.anaconda.com/download

Use the above link to install anaconda and open Jupiter notebook.


##  PROJECT SETUP and RUNNING

The uploaded files include the datasets for the project
-------------------------------------------------------

1. 'Numbers-Alphabets' folder (contains 'train' and 'val' folders to train the model // contains folders with images of numbers and alphabets)
2. 'whiteplate_normal' and 'yellowplate_normal' folders (these contain images of numberplates). 
3. 'Test Number Plates' folder for testing the final output.
4. 'License Plate.ipynb' file - this is the main file that needs to be opened using the Jupyter notebook.

Installing and importing libraries to the code (in anaconda prompt):
------------------------------------------------
* pip install cv2
* pip install pytesseract
* pip install PTL
* pip install numpy
* pip install matplotlib
* pip install webbrowser
* pip install io
* pip install base64
* pip install tkinter
* pip install mplcursors
* pip install tensorflow
* pip install tensorflow numpy
--------------------------------------------------



## How to run the project main file:
---------------------------------

step 1: You need to keep the three folders and main ipynb file on the same directory.

Step 2: open the 'ADM-PROJECT-FINAL.ipynb' file using the Jupyter notebook.

step 3: You will be able to see multiple cells. run each cell one by one.

step 4: If you notice any image paths in the cells, please change them to your local paths of the respective folders and files.


## UI OUTPUT VIEWING

step 5: Once you run the final cell, you will see a window popup with the following text: "Please upload an image with license plate:" and a button labelled as: "Select Image".

Step 6: Click on the 'Select Image' button. you will be asked to upload an image from your local explorer. 

Step 7: Navigate to 'Test Number Plates' folder and select any image and click open.

step 8: You will notice a new tab in your browser with the display of the image you selected and predicted text of the number plate. This is the Main output of our project. You may or may not choose to close this tab.

Step 9: To search another image, you can find the small window with 'select image' button either minimized or open. click the button in that window and select another image. 

Step 10: you can repeat the steps 8 and 9 multiple times.

Step 11: close all the windows and close the ipynb file to close the project.
