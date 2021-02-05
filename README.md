Nepali License Plate Detection.

To detect where the License Plate is I have used opencv, for basic image processing  imutils and pytesseract for Optical Character Recognition.
First of all the image is loaded with the help of opencv and with the help of imutils the image resizing is done. 
The grayscale conversion is done to convert RGB to cvt color image. The bilateral Filter is used to remove some unwanted noise with in the image to make image more clear. The Canny Edge detection is done so that Contours can be applied in the Image edge.

After applying 4 steps on the image finally the contours with more number of Contours i.e 30 is detected and a rectangle box is displayed in the maximum contours area.
