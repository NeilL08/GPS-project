# GPS-project
This project is a GPS-based activity tracking device designed to record outdoor movement and analyze performance. The project aims to improve battery efficiency while providing detailed activity statistics and route visualization.

# current status
Purchased MicoAir M10G-5883 M10 GPS, and Sh 1.0mm 6p wire cable
currently have: esp32

# project Skeleton
- gps cordinates read through UART including longtitude, latitude, speed, and altitude
- create CSV containing timestamps, coordinates, and speed, and plot thorugh python
- adaptive tracking algorithm, sationary for battery saving, moving for normal tracking, and fast movement for prioritizing route detail
  
