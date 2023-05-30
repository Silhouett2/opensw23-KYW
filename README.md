# Team introduction

201811201 원규연

# Topic introduction

ImageBlur
AutoFace-Blur

- 🕵️‍♀️ Blurry Faces
A tool to blur faces or other regions in photos and videos 🕵️‍

- 🙌 Available Codes
1. [auto_blur_image](./src/auto_blur_image.py): Detects and blurs faces _(or objects)_ in a given image automatically due to a Tensorflow model
2. [auto_blur_video](./src/auto_blur_video.py): Detects and blurs faces _(or objects)_ in a given video due to a Tensorflow model
3. [manual_blur_image](./src/manual_blur_image.py): Blurs manually selected faces _(or objects)_

# Results
  
  –Describe the representative results or findings (currently empty)

# Analysis/Visualization

  –Present any analysis or visualizations related to the topic (currently empty)

# Installation

- 🔧🔩 Usage 
1. Clone or download this repo
2. Open [src](/src) folder in CMD
3. Install required packages
   ```bash
   pip install -r requirements.txt
   
<br/><br/>
   
# Run source code
   
- For `auto_blur_image.py`:

   ```bash
   python auto_blur_image.py --input_image <PATH_TO_INPUT_JPG_FILE> --output_image <PATH_TO_OUTPUT_JPG_FILE>  --model_path <PATH_TO_INPUT_PB_FILE> --threshold <THRESHOLD>
   ```
<br/><br/>


- For `auto_blur_video.py`:

   ```bash
   python auto_blur_video.py --input_video <PATH_TO_INPUT_MP4_FILE> --output_video <PATH_TO_OUTPUT_MP4_FILE> --model_path  <PATH_TO_INPUT_PB_FILE>  --threshold <THRESHOLD>
   ```

<br/><br/>

- For `manual_blur_image.py`:

   ```bash
   python manual_blur_image.py --input_image <PATH_TO_INPUT_JPG_FILE> --output_image <PATH_TO_OUTPUT_JPG_FILE>
   ```
    * Select your ROI (Region of Interest)
    * Press <kbd>Enter</kbd>
    * Press <kbd>Q</kbd> to finish **or** any key to select another ROI
<br/><br/>


# Presentation

  –Insert the video link for the final presentation (currently empty)







# Assignment Day 1

 

•Creating a GutHub Page
  –Set the name as opensw23-team_name
  –Write everything on README.md
•Team Introduction
  –Include team member’s names, IDs, and roles
•Topic Introduction
  –Provide an overview of the chosen topic (currently empty)
•Results
  –Describe the representative results or findings (currently empty)

•Analysis/Visualization

  –Present any analysis or visualizations related to the topic (currently empty)

•Installation

  –Explain the installation and running process for the code (currently empty)

•Presentation

  –Insert the video link for the final presentation (currently empty)

 

•Submit the link to your repository to E-Campus.

  –Please note that any late pushes or commits will receive zero credit.
