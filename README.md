# ultrasonic-radar-system
Fully functional, environment scanning system using raspberry pi 3 and arduino uno. 

FEATURES
--CAPTURING IMAGE VIA USB-WEBCAM: For compatibility, we chose to use USB CAM over the standard raspberry camera module to avoid 
  incompatability issues, since the USB port is available for all types of raspberry available.
  
--CAPTURING DISTANCE AND ANGLE OF INTRUSION: Using an ultrasonic sensor controlled through the arduino uno. we can get the distance
  as well as angle of intrusion.
  
--UPLOADING DATA TO WEBPAGE: The project is integrated with tumblr api where data such as photo, intrusion information like andgle and distance
  is uploaded to. we chose the tumblr api for easy integration and also to take advantage of it's mobile phone feature like post-
  notification and admin control.
  
--STREAMING INFORMATION TO WEBPAGE: Using motion software in raspbian, we can stream live-feed through our localhost server. 
  
