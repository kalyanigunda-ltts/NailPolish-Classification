# NailPolish-Classification
Label The Raw Image 


Command Line Arguments

• raw_image: Path to the raw image file.
• labeled_image: Path to the labeled image file.

Running the Script

> Run the script from the command line:
bash

python nail_polish_classification.py path/to/raw_image.jpg path/to/labeled_image.png

> Example

python nail_polish_classification.py images/raw_nails.jpg images/labeled_nails.png

Script Functionality

1 Load Raw Image: The script loads the raw image file using OpenCV.
2 Pre-processing: Converts the raw image to grayscale and resizes it to 256x256 pixels (optional and adjustable).
3 Label Integration: Loads the labeled image and associates each pixel value with the corresponding class label.
4 Display Images: Visualizes the raw and labeled images using Matplotlib.

Assumptions

• The labeled image has the same dimensions as the original image.
• Each pixel in the labeled image represents a numerical value corresponding to a specific polish type.

Error Handling

• The script checks for the existence of the specified image files and raises a FileNotFoundError if they are not found.

Bonus Points

• Interactive labeling functionality is not implemented in this version but can be added for user interaction.
• The script is designed to handle different raw image formats (e.g., JPG, PNG).


