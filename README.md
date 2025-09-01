# Harry_potter_invisibility_cloak
🪄 Invisibility Cloak using Python & OpenCV

A real-time Harry Potter–style invisibility cloak built with Python and OpenCV.
This project detects a colored cloak (red by default) in front of the webcam and replaces it with the captured background, creating the illusion of invisibility.

---------------------------------------------------------------------------------
📸 Demo

(Replace with your demo video or screenshots)

🚀 Features

Real-time video processing with OpenCV

HSV color space detection for accurate cloak masking

Morphological transformations to reduce noise

Contour filtering to ignore small false detections

Works with any color cloak (adjustable via HSV ranges)
------------------------------------------------------------------------------------------
⚙️ How It Works

Capture the background (without the cloak).

Detect the cloak’s color using HSV color thresholds.

Create a mask of the cloak area.

Replace the cloak region with the stored background.

Display the final output in real-time.

🛠️ Tech Stack

Python 3.x

OpenCV

NumPy
--------------------------------------------------------------------
📦 Installation


Install dependencies:

pip install opencv-python numpy
------------------------------------------------------------------------
▶️ Usage

Run the script:

python harry.py


Controls:

ESC → Quit the program

b → Re-capture the background
----------------------------------------------------------------------------------
🎨 Changing Cloak Color

By default, the cloak is red.
To change the cloak color, modify the HSV ranges in the code:

# Example for yellow cloak
lower_yellow = np.array([22, 150, 120])
upper_yellow = np.array([30, 255, 255])

🌟 Future Improvements

Add GUI sliders (trackbars) to adjust HSV values live

Support for multiple cloak colors

Deploy as a simple desktop app

🙌 Acknowledgements

Inspired by the Harry Potter invisibility cloak 🧙‍♂️✨
Built with ❤️ using Python and OpenCV.
------------------------------------------------------------------------------------
My Linkdin
linkedin.com/in/shrey-bajpai-98278a282
