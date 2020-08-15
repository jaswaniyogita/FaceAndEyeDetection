OpenCV uses machine learning algorithms to search for faces within a picture. Because faces are so complicated, there isn’t one simple test that will tell you if it found a face or not.

For this, I have have used Haar Cascade. A Haar Cascade is basically a classifier which is used to detect the object for which it has been trained for, from the source.

The methodology of face detection can be applied to landmark (e.g., eyes, nose tip, and mouth) localization, which can then be utilized to face geometrical normalization.


Environment Setup required :

1. Jupyter Notebook

2. Python — OpenCV, numpy

3. Insert haarcascade_eye.xml & haarcascade_frontalface_default.xml files in the same folder.
