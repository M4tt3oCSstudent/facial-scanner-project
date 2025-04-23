Overview: This project is built using cv2 to capture images and scan them, numpy as to hold to the images of the people related to the dataset, 
face_recognition which of course is the main part as to name the people in my dataset model, with PIL, Image, ImageOps as to set the images all vertical and organize them nicely.
Matplotlib as to help display the images once processed

Challenges: The main challenge I had faced was originally trying to get this to work in video to get people to be recognized in live time and especially with disguises
however it proved to be diffilcult when running Notebook in Ubuntu and it didn't support video feed at all and given scalability I believed that it wouldn't be done in time so I ended 
up with using pictures. Along with this, was getting the images to display vertically as certain images that I uploaded would automatically be horizontally and would not be scanned so I had to use the ImageOps library
to automatically set up the images vertically.

What I learned: I learned first of how use a model to scan faces of certain people and be identified, print images of the scanned results when running the code,
loop all images in a dataset to print all images with scanned results, rearrange the images as to automatically set them up vertically and lastly what I learned
was how to add new people to my model and get them named based on their image name folder.
