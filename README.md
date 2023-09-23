# Sharpening and Sizing Images Using OpenCV
A simple step-by-step program using OpenCV and Google Colab for beginners that will allow you to sharpen and resize images.
<img width="820" alt="Screen Shot 2023-09-24 at 12 22 11 AM" src="https://github.com/Yara-Khedr/Image-Sharpening-and-Sizing-using-OpenCV/assets/141963941/6d8d5454-da8c-47e1-a563-0ea11eb9a3fb">


## What does this code do?
By following the steps of this project, you will be able to read and display images, sharpen blurry picutres to make them clearer, re-size any image, as well as display pictures side-by-side.

  ### Steps of Filtering An Image:
  1. Import libraries (numpy,cv2, cv2_imshow from google.colab.patches)
  1. Read and display images (cv2.imread(), cv2_imshow())
  1. Define sharpening kernels (np.array())
  1. Sharpen Image (cv2.filter2D())

  ### Steps Of Resizing An Image:
  1. Resize image (cv2.resize())
  1. Find dimension of image (image.shape[])
  1. Border smaller image (cv2.copyMakeBorder())

  ### Steps Of Displaying Images Side-By-Side:
  1. Display concatenated images
* cv2.hconcat() for horizontal concatination
* cv2.vconcat() for vertical concatination
