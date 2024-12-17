# CSC 7901 Capstone Tiny ML
The repo contains the locally run experiments and data processing notebooks used throughout the capstone.

## **File Descriptions:**
- **camera_capcture_code.zip**: code for capturing image using Arduino Nano with camera 0v7670
- **models.zip**: all variants of trained res8 and random forest models
- **edge_impulse_processing_fn.zip**: refactored code for running Edge Impulse DSP code locally in notebooks
- **random_forest.ipynb**: notebook for Random Forest experiments
- **res8.ipynb**: notebook for res8 experiments 

-------------------------------------------------------------------------------------------------------------------------------------------

For the camera capture, the file descriptions included are as follows: 
- **camera_capture_w_processing_Ov7670**: Arduino sketch
- **process_camera_data**: code that runs on a third-party tool that decodes serialized captured data by the camera and displays it (refer to this link to download third-party app called Processing: https://processing.org/download). The third-party app was discovered from this tutorial on running camera capture (https://blog.arduino.cc/2020/06/24/machine-vision-with-low-cost-camera-modules/). 
