# Autonomous-Vehicle-Lane-detection

This is opencv-python based program to identify lanes in a video. Output of the executed videos can be found in the output_videos folder

## Piepeline followed: 
* These steps are performed on each frame in a video, you obviously figured that out :)
> Convert the image into Grayscale

> Apply canny on the gray_image created

> Reduce the noise in the image using gaussian_blur on gray_image

> Apply canny to the gaussian_image by specifying low and high thresholds

> Now find the hough_lines and draw the lines onto the image

> Then find the Area of interest based on the hough_image, finally addWeight function is used to represent the lanes identified

### Comments are specified at each phase of the code for better understanding, have fun learning
