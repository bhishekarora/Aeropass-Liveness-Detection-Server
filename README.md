# Aeropass-Liveness-Detection-Server
Inspect multiple frames and find liveness by calculating facial vectors 


# Tech
 - Multiple facial vectors (4096 1d) captured via OpenCV sent to backend and distance between facial landmarks used to find liveness

   
<img src="aeropasslivenessdetection.png" width="200">

# EP 
 - '/check-liveness'  -- True if human detected , false if photo or static image.


> Works with Aeropass App , it sends frames to this EP and algo captures distances between landmarks.


# Ref 
<img src="https://github.com/user-attachments/assets/c0dc5879-140a-4918-bb6f-7ba86c7e6c0a" width="200">
<img src="https://github.com/user-attachments/assets/10daa173-8dd8-41d9-a612-337c82d3e47a" width="200">


