# Watermark_Application
This code demonstrates how to add watermarks to images using two different methods:

# Method 1: Adding a Transparent (PNG) Logo to an Image

Begins by importing necessary libraries such as OpenCV and Matplotlib.
Reads the image (leaves.jpg) and the transparent logo (opencv_logo.png).
Resizes the logo to 10% of its original dimensions.
Separates the color and alpha channels from the logo.
Determines the region of interest (ROI) in the image where the logo will be placed (center of the image).
Creates masks for the ROI and the logo.
Blends the ROI and the logo using logical operations.
Inserts the watermarked ROI into the original image.
Saves the final watermarked image.

# Method 2: Watermarking (adding a semi-transparent logo)

Follows similar steps as Method 1 up to determining the ROI and creating masks.
Uses the addWeighted() function to blend the logo with the image ROI, adding a transparency effect.
Inserts the watermarked ROI into the original image.
Saves the final watermarked image.
Both methods are demonstrated with their respective results (watermarked_method_1.jpg and watermarked_method_2.jpg), allowing for comparison between the two approaches.

The code provides detailed explanations and visualizations at each step, making it easy to understand the process of adding watermarks to images using OpenCV.
