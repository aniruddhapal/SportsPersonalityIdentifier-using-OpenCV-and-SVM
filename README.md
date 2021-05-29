# SportsPersonalityIdentifier-using-OpenCV-ML
This is a computer vision project which identifies sports personality if you upload a front face , eyes open image of any one of the 5 personalities.
I have used OpenCV Haar cascade to detect the Face and Eyes, and stored the cropped images in respective folders.
I have tried Logistic Regression, SVM and Random Forest to train the model.
SVM performed the best, hence created the pickle file using the same.
This is an end-to-end project, with user interface created using HTML, JavaScript and CSS.
After uploading the image, once you click on the Classify button it classifies the image using the pickle file and display the probability score of all 5 personalities.
Probability score is maximum for the matching personality.
