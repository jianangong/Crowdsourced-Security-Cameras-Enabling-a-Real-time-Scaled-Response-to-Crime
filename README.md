# Crowdsourced Security Cameras Enabling a Real-time Scaled Response to Crime
## Abstract
City of Paterson plans to utilize crowdsourced security cameras to reduce the crime rate by getting a real-time response to the crime and recognize the social distancing violation in this COVID-19 situation. By analyzing geospatial data, the team plotted the overlapped heatmap of both crime and COVID-19 response and found the best places to install cameras. The further clustering of temporal and spatial patterns of crime helped the city to better monitor violent crimes at midnight and theft in the early morning, while the time prediction for each census tract provided the police key regulatory direction in the future.  After the installation of cameras, the team developed a dashboard of public surveillance cameras for social distance detection by using YOLO4, the object detection algorithm. 


## Introduction
City Paterson is going to solve the crime problems by using Crowdsourced Security Cameras and collaborative policing. The city has always been handling the relatively high crime rate compared with other cities in NJ. In the meanwhile, due to the current COVID-19 situation, another type of violation--social distancing violation surges. Our sponsor wants to properly place and utilize cameras to kill two birds with one stone which means placing the camera appropriately which can both detect crime and social distance violation.
<br></br>
The scope of the program switched from Crowdsourced Security Cameras to collaborative policing using data and models which is advocated by our sponsor. So, our study focuses on: 1.find out where to install those cameras by overlapping  the city crime and COVID-19 response call data 2. allocate the police force temporally and spatially based on data analytics and modeling 3. develop a Yolo-based model to detect social distancing and blank frame (no person in the frame)


  ### Please fork the repository and give credits if you use any part of it. :slightly_smiling_face:
  ## It took me time and effort to code it.
  ## I would really appreciate if you give it a star. :star:
  ## YOU ARE NOT ALLOWED TO COMMERCIALIZE OR MONETIZE THIS CODE IN ANY FORM.(Not even youtube)
 
#### v1.0 output:

![](output.gif)

#### v2.0 output:
![](op2.gif)

## Features:
* Get the areal time nalytics such as:
   - Number of people in a particular area
   - Number of people in high risk
   - The extent of risk to a particular person.
* Doesn't collect any data of a particular person
* Stores a video output for review


## Installation:
* Fork the repository and download the code.
* Download the following files and place it in the same directory
   - https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg
   - https://pjreddie.com/media/files/yolov3.weights
* For slower CPUs, use yolov3-tiny (link in the code comments)
* Install all the dependenices
* Run social_distance_detection.py
### Credits:
##### We want to appreciate the great help from Ankush Chaudhari who taught the team a lot in terms of yolo and distance calculation
