# Implementation of Erosion and Dilation Using OpenCV

## AIM

To write a Python program using OpenCV to perform morphological operations such as Erosion and Dilation on an image.

The program performs the following operations:

- Image Erosion
- Image Dilation

## SOFTWARE USED

- Anaconda – Python 3.7
- Jupyter Notebook / VS Code
- OpenCV (cv2)
- NumPy
- Matplotlib

## ALGORITHM

**Step 1:** Import the required libraries: OpenCV, NumPy, and Matplotlib.

**Step 2:** Create a blank image using NumPy.

**Step 3:** Insert text onto the image using OpenCV's text drawing function.

**Step 4:** Display the original image.

**Step 5:** Create a structuring element (kernel) of suitable size.

**Step 6: Image Erosion**
- Apply the erosion operation using the created kernel.
- Remove pixels from the boundaries of foreground objects.
- Display the eroded image.

**Step 7: Image Dilation**
- Apply the dilation operation using the same kernel.
- Add pixels to the boundaries of foreground objects.
- Display the dilated image.

**Step 8:** Compare the original, eroded, and dilated images.

## PROGRAM DEVELOPED BY

**Name:** Varun A

**Register No:** 212224240178

## PROGRAM

The program is implemented using Python and OpenCV in Jupyter Notebook.

The following morphological operations are implemented:

1. Image Erosion
2. Image Dilation

A blank image is created using NumPy, and text is inserted using OpenCV. A 5 × 5 structuring element is used to perform the morphological operations.

## OUTPUT

### 1. Original Image

<img width="742" height="365" alt="image" src="https://github.com/user-attachments/assets/e57391fc-c26a-447f-923b-61aa13087a14" />


### 2. Erosion

<img width="951" height="271" alt="image" src="https://github.com/user-attachments/assets/2ea87184-526f-4447-a1d0-949912d903f7" />


### 3. Dilation

<img width="1053" height="272" alt="image" src="https://github.com/user-attachments/assets/5da44be6-9bc5-441b-b5ba-6a5135f894d6" />


### 4. Comparison

<img width="1341" height="300" alt="image" src="https://github.com/user-attachments/assets/a04362f9-d566-4d88-a6e4-e71d71d5c21f" />


## RESULT

Thus, the morphological operations Erosion and Dilation are successfully implemented using OpenCV.
