# computer-vision
This includes all program which involve computer vision concept
# 🧙‍♂️ AR Invisibility Cloak (OpenCV)

## ✨ Overview

This Python script utilizes the OpenCV library (`cv2`) to create a simple yet effective Augmented Reality (AR) invisibility cloak effect. The core mechanism involves detecting a specific color (currently configured for **Olive Green**) in the live video stream and replacing those pixels with a static background image captured earlier.

The effect is achieved using color thresholding in the HSV color space, which is robust against changes in lighting and shadow.

## 🚀 Features

* **Real-time Video Processing:** Processes live video feed from a webcam.
* **Background Capture:** Automatically captures a background image to use as the base for the illusion.
* **Color-Based Cloaking:** Uses HSV color thresholding to detect and segment the cloak object.
* **Morphological Cleanup:** Employs opening operation to clean up the detection mask, minimizing noise.
* **Configurable Cloak Color:** Easy to modify the code to use any color (e.g., Red, Blue, Black, White).

## 📋 Prerequisites

Before running the script, ensure you have the following installed:

* Python 3.x
* A working webcam or video capture device.

## 📦 Installation

Clone the repository and install the necessary Python libraries:


## ▶️ How to Run

1.  **Prepare the Cloak:** Get a solid piece of fabric or paper matching the target color (e.g., **RED**).
2.  **Execute the Script:**
    ```bash
    python AR_invisibility_Cloak.py
    ```
3.  **Background Capture:** The script will open the webcam feed and pause for **3 seconds (`time.sleep(3)`)**. **Step away from the camera during this time** so the program can capture the empty background.
4.  **Activate Cloak:** Once the main video window appears, move into the frame and hold the **Olive Green** object in front of you. The object should disappear, revealing the captured background.
5.  **Exit:** Press the **ESC** key to close the program windows.

## 🎨 Customizing the Cloak Color

The invisibility effect relies on detecting a precise range of Hue (H), Saturation (S), and Value (V). The current configuration is set for **RED**.
Link for the video .


https://drive.google.com/drive/folders/11kswv6K5-4xwgNoEeEVCBCrLAEchP3e_?usp=sharing
	
	
