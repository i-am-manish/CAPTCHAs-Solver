# About
This is a CAPTCHAs slover.
Not my original work, written after learning.

### Before you get started

To run these scripts, you need the following installed:

1. Python 3
2. OpenCV 3 w/ Python extensions
3. The python libraries listed in requirements.txt
 - Try running "pip3 install -r requirements.txt"

### Step 1: Extract single letters from CAPTCHA images

Run:

python3 extract_single_letters_from_captchas.py

The results will be stored in the "extracted_letter_images" folder.


### Step 2: Train the neural network to recognize single letters

Run:

python3 train_model.py

This will write out "captcha_model.hdf5" and "model_labels.dat"


### Step 3: Use the model to solve CAPTCHAs!

Run: 

python3 solve_captchas_with_model.py


SCREENSOT OF TRAINING PROCESS IS ATTACHED too
