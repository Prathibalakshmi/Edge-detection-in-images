# Edge-detection-in-images
EDGE DETECTION OF IMAGES
Edges define the boundaries between the different regions in an image which helps in matching the pattern,segment and recognize an object. In simple threshholding , the theshold value is global, which is prone to fail in m any cases. Adaptive thresholding is a modefied method wgere the threshold value is calculated for each pixel based on a smaller region around it. Therefore there are different threshold value for different regions.

AIM:
Use different thresholding methods for edge detection and use that as a mask to give color to all the edges.
STEPS:
- Using open cv converting an image to gray scale.
- Implementing Edge Detection using canny edge detection.
- Then applying Simple Thresholding.
- Then Adaptive /OTSU thresholding
- After getting good results use the result as a mask to give a color to all edges.
