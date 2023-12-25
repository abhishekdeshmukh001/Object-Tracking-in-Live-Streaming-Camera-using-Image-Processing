## Title: Object Tracking in Live Streaming Camera using Image Processing

### Overview:
* This project involves the implementation of a real-time traffic tracking system to monitor and analyze the intensity of transportation on specific routes. 
* The system utilizes computer vision techniques, including background subtraction and contour detection, to track vehicles in live traffic camera feeds. 
* The tracking precision is achieved through the integration of the **'EuclideanDistTracker'** class.


### B. Key Features
* **Background Subtraction:** Implemented OpenCV's **'createBackgroundSubtractorMOG2'** for dynamic background subtraction, allowing the system to focus on moving vehicles within the traffic scene.

* **Contour Detection:** Utilized contour detection to identify and extract vehicles from the live traffic camera feed. This step is crucial for tracking moving objects accurately.

* **Region of Interest (RoI):** Defined Regions of Interest within the traffic camera feed to capture specific areas of interest, enhancing the system's efficiency in monitoring targeted routes.

* **Object Tracking:** Implemented the **'EuclideanDistTracker'** class to assign unique IDs to tracked vehicles based on their movement patterns. This enables the system to track multiple vehicles simultaneously.

### C. Implementation Details
The system processes each frame from the live streaming camera feed by performing the following steps:

**1] Object Detection:** Utilizes background-subtracted frames to detect objects (vehicles) through contour analysis. Small elements are filtered out based on area criteria.

**2] Object Tracking:** Applies the EuclideanDistTracker to update and track the detected objects over consecutive frames. Each tracked object is assigned a unique ID, facilitating precise monitoring.

**3] Visualization:** Draws bounding rectangles around tracked vehicles, displaying their unique IDs. Regions of Interest (RoIs) within the traffic camera feed are outlined to capture specific areas of interest.


## Output

![Object Tracking](https://github.com/abhishekdeshmukh001/Object-Tracking-in-Live-Streaming-Camera-using-Image-Processing/blob/main/Object%20Track%20Live%20Stream.gif)


## 🔗 Link
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-sachin-deshmukh/)


## Authors

- [@abhishekdeshmukh001](https://github.com/abhishekdeshmukh001)
