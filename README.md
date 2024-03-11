To run these scripts, you need the following installed:

Python libraries listed in requirements.txt
Run "pip3 install -r requirements.txt"

Run python3 extract_single_letters_from_captchas.py

The results will be stored in the "extracted_letter_images" folder. The folder already has images so delete them before running


Run: train_model.py

This will write out "captcha_model.hdf5" and "model_labels.dat"



Run: python3 solve_captchas_with_model.py

This will run solve detech the captachas