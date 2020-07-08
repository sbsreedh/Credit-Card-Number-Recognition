## Credit-Card-Number-Recognition
OpenCV to identify Credit Card Number from a picture of Card

#### Method


Steps of identifying the number:
1. Detecting the four groups of four numbers on the credit card via various image processing techniques, including morphological operations, thresholding, and contour extraction.
2. Extracting each of the individual digits from the four groupings, leading to 16 digits that need to be classified.
3. Applying template matching to each digit by comparing it to the OCR-A font to obtain our digit classification.
4. Examining the first digit of the credit card number to determine the issuing company.

#### Result

![Screenshot 2019-06-04 at 10 10 41 PM](https://user-images.githubusercontent.com/29504448/58886061-da6ab500-8715-11e9-9df5-f64a64301f0b.png)








