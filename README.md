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
  
  -decrease Threshold then the blurring criterion is harder<br/>
  -but also there is incorrect output <br/>
  -when Threshold >= 1 this program can't blur anything<br/>

# Analysis/Visualization

  –Present any analysis or visualizations related to the topic (currently empty)
  <br/><br/>
  -before 
  <br/>
  ![test1](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/61c39943-978b-4c04-9c7d-0bb40b0be1db)
  <br/><br/>
  -after Threshold = 0.4
  <br/>
  ![output1](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/0b151b0c-0b2c-45d4-b179-25a961adf431)
  <br/><br/>
  -before
  <br/>
  ![test2](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/1b9d0b87-4f83-427c-8e9f-a7f34a9f0ceb)
  <br/><br/>
  -after Threshold = 0.4
  <br/>
  ![output2](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/bf4d2070-211e-4284-a57c-62dd8d4fecfb)
  <br/><br/>
  -before
  <br/>
  ![test3](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/1311130d-8f8b-4ae3-8a73-19186a56f958)
  <br/><br/>
  -after Threshold = 0.4
  <br/>
  ![output3](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/cc48999d-554a-4604-8921-9ead3fe5d561)
  <br/><br/>

  <br/><br/>
  ### Threshold Adjustment
<br/>
  before
  <br/>
    ![test7](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/723dc77d-9d0d-407e-95ee-70b439873a2b)

<br/><br/>
<br/><br/>
  -Threshold = 0.4
  <br/>
  ![output7](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/e28b1527-8d98-430f-ab1a-e56d945ad864)
<br/><br/>
  -Threshold = 0.1
  <br/>
  ![output7-2](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/22eea773-7592-4de5-b9c4-133ec9daeb37)
<br/><br/>
  -Threshold = 0.05
  <br/>
  ![output7-3](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/eebc95e8-7b70-4a64-a3fd-96c777bf90ee)
<br/><br/>



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
