# Team introduction

201811201 원규연 <br/><br/>


# Topic introduction

ImageBlur    
    
AutoFace-Blur

- 🕵️‍♀️ Blurry Faces
A tool to blur faces or other regions in photos and videos 🕵️‍

- 🙌 Available Codes
1. [auto_blur_image](./src/auto_blur_image.py): Detects and blurs faces _(or objects)_ in a given image automatically due to a Tensorflow model
2. [auto_blur_video](./src/auto_blur_video.py): Detects and blurs faces _(or objects)_ in a given video due to a Tensorflow model
3. [manual_blur_image](./src/manual_blur_image.py): Blurs manually selected faces _(or objects)_

# Analysis/Visualization
  
  -decrease Threshold then the blurring criterion is harder<br/>
  -but also there is incorrect output <br/>
  -when Threshold >= 1 this program can't blur anything<br/>  
  -If the resolution is high, the program pouts out of the screen.<br/>  
  -This program supports only .jpg, .mp4 files
  

# Results


  <br/><br/>
  
  `auto_blur_image.py`
  
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

### Threshold Adjustment

<br/>
-before
<br/><br/>

![test7](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/795ee9f3-5ab4-4da3-9e63-060b9100d1a1)


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

- before

<br/><br/>

![test9](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/65714440-9f21-49eb-8eef-a28c51e1dd66)

<br/><br/>

  -Threshold = 0.4
 
<br/><br/>

![output9](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/7dde57c3-0f30-41b5-9a67-7189ce89b280)


<br/><br/>

  -Threshold = 0.1

<br/><br/>

![output9-2](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/9bdfa220-bcd5-4e3d-b2cf-60e62f43d778)


<br/><br/>


`auto_blur_video.py`

<br/><br/>

- before

https://github.com/Silhouett2/opensw23-KYW/assets/125653123/2c8a30c8-bfb2-4af7-980c-fb822ea2de3d


<br/><br/>

- after



https://github.com/Silhouett2/opensw23-KYW/assets/125653123/7cf0cb7f-2f40-477f-b671-d89397db01be



<br/><br/>

`manual_blur_image.py`

<br/><br/>

- before

<br/><br/>

![test5](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/09da00e7-f2fe-44a3-878a-dd5d87abcaab)

<br/><br/>

![output5-2](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/5125dc39-1fcf-40d0-b58a-7a7c46a39498)

<br/><br/>

- after

<br/><br/>

![output5](https://github.com/Silhouett2/opensw23-KYW/assets/125653123/a06abb85-e214-4f7d-a815-f15c9c588ac7)



<br/><br/>


# Installation

- 🔧🔩 Usage 
1. Clone or download this repo
2. Install required packages    
   ```bash
   pip install numpy
   ```
   ```bash
   pip install tensorflow 
   ```
   ```bash
   pip install opencv-python
   ```  
    numpy==1.19.4  
    tensorflow==2.3.1  
    opencv==4.5.0  
3. Open [src](/src) folder in CMD

   
# Run source code
   
- For `auto_blur_image.py`:

   ```bash
   python auto_blur_image.py --input_image <PATH_TO_INPUT_JPG_FILE> --output_image <PATH_TO_OUTPUT_JPG_FILE>  --model_path <PATH_TO_INPUT_PB_FILE> --threshold <THRESHOLD>
   ```

- example :  
   ```bash
   python auto_blur_image.py --input_image ../pictures/test1.jpg --output_image ../pictures/output1.jpg --model_path ../face_model/face.pb --threshold 0.4
   ```
   
<br/><br/>

- When you enter the command, a preview image file is printed, and if you click and close the x-box of the file, the program ends and a blurred image file is created.

<br/><br/>

- For `auto_blur_video.py`:

   ```bash
   python auto_blur_video.py --input_video <PATH_TO_INPUT_MP4_FILE> --output_video <PATH_TO_OUTPUT_MP4_FILE> --model_path  <PATH_TO_INPUT_PB_FILE>  --threshold <THRESHOLD>
   ```
   
- example :  
   ```bash
   python auto_blur_video.py --input_video ../videos/test1.mp4 --output_video ../videos/output1.mp4 --model_path ../face_model/face.pb --threshold 0.4
   ```
   <br/><br/>
   - When you enter the command, a preview video file is printed, and if you click and close the x-box of this file, a blurred video file is created as the program ends.
   <br/><br/>
   
- For `manual_blur_image.py`:

   ```bash
   python manual_blur_image.py --input_image <PATH_TO_INPUT_JPG_FILE> --output_image <PATH_TO_OUTPUT_JPG_FILE>
   ```

- example :  
   ```bash
   python manual_blur_image.py --input_image ../pictures/test5.jpg --output_image ../pictures/output5.jpg
   ```
    * Select your ROI (Region of Interest)
    * Press <kbd>Enter</kbd>
    * Press <kbd>Q</kbd> to finish **or** any key to select another ROI
    * Similarly, when all is complete, a preview image file will be printed, and if you click and close the x-box of this file, the program will exit and create a blurred image file.
<br/><br/>


# Presentation


https://youtu.be/WJA9xKwgGno


# Original source  

https://github.com/asmaamirkhan/BlurryFaces

