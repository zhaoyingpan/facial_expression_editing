# 592final_project_2021fall
This is README of the 592 final project of team 4, 2021 fall.

THe final folder contains 
* two ipynb file (592code_final.ipynb, preprocessing.ipynb)
* two original images (original1.jpg, original2.jpg)
* two preprocessed images (pic1.jpg, pic2.jpg)
* one original video (original_video.mp4)
* one preprocessed video (2.mp4)
* two txt file of facial landmarks from pic1.jpg and pic2.jpg (pzy1.txt, pzy2.txt)
* two zip file (ldm.zip, checkpoints.zip)
    ldm.zip contains landmarks for every frame in the 2.mp4, checkpoints.zip contains pretrained model which we will use later.

For preprocessing.ipynb:

*If you already have pic1.jpg, pic2.jpg, 2.mp4, ldm.zip, pzy1.txt, pzy2.txt, you can skip this notebook.

* You can align your original images or videos, and get the facial landmark file in preprocessing.ipynb.

* You will get pic1.jpg, pic2.jpg, 2.mp4, ldm.zip, pzy1.txt, pzy2.txt, from original1.jpg, original2.jpg, original_video.mp4.

* In preprocessing.ipynb, first upload the original1.jpg, original2.jpg, original_video.mp4, then follow every step in the paragraph "Image Alignment", "Video Alignment", "Extract landmarks for every frame in the video", "Record the difference between the landmarks of input image and every frame".

    1. Image Alignment: crop and rotate the original photo, and resize it to 256\*256
    2. Video Alignment: crop and rotate every frame in the video, and resize it to 256\*256
    3. Extract landmarks for every frame in the video: input a video, will save landmarks of every frame as txt files in a folder.
    4. Record the difference between the landmarks of input image and every frame: this part will save the landmark difference between input image and every frame in the video. The output file is pzy1.txt, pzy2.txt

For 592code_final.ipynb:
    *main code for generating video

* First upload the pic1.jpg, pic2.jpg, 2.mp4, ldm.zip, pzy1.txt, pzy2.txt, then just follow every step in this notebook.

    1. 

