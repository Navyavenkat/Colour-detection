# Colour-detection
# Multiple Colour Detection
 A color detection algorithm identifies pixels in an image that match a specified color or color range. The color of detected pixels can then be changed to distinguish them from the rest of the image.
# Work Flow
# Step 1:
    Input: Capture video through webcam.
# Step 2:
   Read the video stream in image frames.
# Step 3:
    Convert the imageFrame in BGR(RGB color space represented as three matrices of red, green and blue with integer values from 0 to 255) to HSV(hue-saturation-value) color space.
    Hue:describes a color in terms of
    saturation: represents the amount of gray color in that color and
   value:describes the brightness or intensity of the color. This can be represented as three matrices in the range of 0-179, 0-255 and 0-255 respectively.
# Step 4:
   Define the range of each color and create the corresponding mask.
# Step 5:
   Morphological Transform: Dilation, to remove noises from the images.
# Step 6:
   Bitwise_and between the image frame and mask is performed to specifically detect that particular color and discrad others.
# Step 7:
  Create contour for the individual colors to display the detected colored region distinguishly.
# Step 8:
  Output: Detection of the colors in real-time

  ![a](https://github.com/Navyavenkat/Colour-detection/assets/94165327/300fab41-5c78-44aa-bc1c-2f24697a5bff)

# Output
  ![image](https://github.com/Navyavenkat/Colour-detection/assets/94165327/f09a9096-d8e3-4935-a42d-84f40b994bcf)
