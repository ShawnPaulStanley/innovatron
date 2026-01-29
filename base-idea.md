# Base Idea
## Hardware  
This is how the microscope takes the cyto image.  
Need something to control how the camera slides the microscope and takes an image.  

### Note: this hardware must be a mod/extension that can be applied on existing microscopes.  

### Following this
Send the image via ESP32 to the server.  

## Software
Input is the previous image.  
Creates heatmap and processes and points out malignant cells part.  

# Flow of Action
For the base idea, put an extension on top.  
This extension will contain the camera and the necessary hardware to send the image (ESP32, etc).  

The image is sent to the server machine, which performs the analysis, and then returns the analysed image back to this extension.  

On the very top of the extension is a screen. This screen will contain a live analysis of the cyto image.  

The doctor can then choose to move the microscope to search the slide.  
Once they've found it, they can stop.  
