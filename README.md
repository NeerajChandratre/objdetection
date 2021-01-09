##Object Detection Overview
I share my first project on github. I ran the object detection project using Darknet using custom trained weights for detecting plants and the results obtained are from the first trained weights. Although the training needs further improvements, the results obtained are substantial as they have a moderate level of accuracy in detection.                     ##STEPS WHICH I DID FOR OBJECT DETECTION 
*Install opencv and cuda drivers for faster performance
*Collect images and keep them in obj folder
*Generate annotations of the images
*Made changes to the yolov3 config file. During training of weights, I set the batch size to 64 and subdivisions to 32 (You can change this to 16,32,64 as per your PC configurations. If the PC shows the cuda out of error message when set to 16, try with higher values)
