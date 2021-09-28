# Measure-Me

Measure-Me is an app concept developed to extract measurements such as height, waist, chest, and others via images without going through the hassle of measuring tapes.
<br>

Two methods were used. The first identifies a reference object in the image and calculates the number of pixels needed to make up 1 cm. Then the top and bottom point of a person is located to count the pixels and then calculate the final height. Similarly, the second method produces the same types of calculations however the identification of the object and person’s top and bottom points is done more manually by the user themselves.
<br>

Both methods were slightly off with the manual method doing a bit better. However, the room for improvement is much bigger for the first method especially if a pre-trained model that detects the outline of a human body existed/were to exist.
<br>

Medium article that goes into detail: https://medium.com/@hassan.dbouk141/measure-me-an-app-concept-to-extract-measurements-from-images-44e49e6a552
<br>

Files in this repo:

- Trackbars.ipynb : Jupyter Notebook used for adjusting parameters in real-time to play around Computer Vision concepts. I mainly used it to find the rectangular shaped card on the A4 paper

- Measure-Me-Simple.ipynb : Jupyter Notebook to apply the 2nd method (user pinpointing the top and bottom points). Explained more thoroughly in the medium article and via comments inside the notebook

- Measure-Me : Main Python notebook to be uploaded to and used at Google Colab. Make sure to double check the directories at the beginning.

- CV_Example.png : sample image file to play around and test the trackbars in Trackbars.ipynb

- FrontX.jpeg : sample image file to test the code
