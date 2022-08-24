Case Study : Pan Card Tampered Detection with Flask.

Description :  This project can be used in different organisation where customers or users need to provide any kind of id in order to get themselves verified. The organisation can use this project to find out whether the ID is original or fake. Similarly this can be used for any type of ID like Aadhar Card, Pan Card and more.

Step to be Followed in this project 

1 : Get the Image form the user
2 : Chceck for size and format of the image
3 : Change shape and size of image according to the original image
4 : Convert the image into grayscale
5 : Find the similarity index of the images
6 : Find the threshold of the image
7 : Finding contour and grab those contour using imutils
8 : Draw a bounding rectangle using these contours
9 : Plot the differences, thresold, original image and tempered image
10 : Compare all the images and check the similarity score to decide tampering.




NOTE : This is not my project. I used only for the Educational Purpose.

Step to run application:
Step 1:	Create the copy of the project.
Step 2: Open command prompt and change your current path 
to folder where you can find 'app.py' file.
Step 3: Create environment by command given below-
conda create -name <environment name>
Step 4: Activate environment by command as follows-
conda activate <environment name>
Step 5: Use command below to install required dependencies-
python -m pip install -r requirements.txt
Step 6: Run application by command;
python app.py
You will get url copy it and paste in browser.
Step 7: You have sample_data folder where you can get images to test.
