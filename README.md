# Gesture2English - An ASL-to-text translator

This project focuses on creating an AI-based ASL-to-text translator using AlexNet that has been trained using more than 80,000 training image, and YOLO for the hand detection

(Note: Before running the code, make sure that the root folder is set up properly and the assumed folder exists. In addition, this code is meant to be run on Google Colab, thus so there might be side effects when running outside Colab. The YOLO and AlexNet weights are not uploaded to this repository, and instead are attached as Google Drive links since their file sizes are too big.)

**Gesture2Eng.ipynb** - The main notebook where all the coding and process happens

**Hello ASL vid.mp4 & COLAB.mp4** - Two sample videos for the ASL

**sample_img.jpg, safari_2.jpg & sample_img_cropped.jpg & safari_2_cropped.jpg** - Two sample images and their cropped results for image input to the YOLO + AlexNet model

**/images & /images2** - The resulting parsed images from video "Hello ASL Vid" and "COLAB" respectively and their cropped counterpart

**/Kaggle** - A directory to download the Kaggle dataset directly

**Link to yolo weights**: https://drive.google.com/file/d/1axIIOKUTbPiTSabrjEr7w5KObpITgwii/view?usp=sharing

**Link to best AlexNet weights**: https://drive.google.com/file/d/17FTTeXbEJo4iT1PaI3BZX9zqscU4Oyh2/view?usp=sharing

**Link to YOLO traning files**: https://drive.google.com/file/d/16z-LfQc5pMtefcHIevp1AT4yO1bbBx0A/view?usp=sharing
