# car_detector
A simple guide to detect and track cars from a video.

# Pretrained CascadeClassifier is used to detect cars from a video.

Steps to follow:
> 1. Download vehicles.xml file shared alongwith.
> 2. Import and assign some variable name to the same.
     car_cascade =  cv.CascadeClassifier('path/to/xml')
> 3. Use detectMultiScale from carCascade
> 4. Draw rectangles using cv2 to the detectede car
> 5. input a video and watch output using cv2.imshow()
