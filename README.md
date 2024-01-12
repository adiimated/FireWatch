# FireWatch

FireWatch is a groundbreaking fire detection tool developed during UB Hacking 2023. Leveraging the power of YOLOv5 and advanced computer vision, FireWatch is designed to identify signs of fire in video feeds more efficiently than traditional methods. This tool is crucial for early fire detection, offering a significant advancement in safety and emergency response measures.

## Features

- Upload video to check for presence of fire
- Perform fire detection on the uploaded video.
- Display the processed video with detected fire.

## Prerequisites

Before running the application, make sure you have the following prerequisites installed on your system:

- Python 3
- Flask
- Flask-Ngrok
- OpenCV (cv2)
- YOLOv5

## Dataset

We got the data from the link below which has 3527 training images and their labels, 75 validation images and their labels as well as 75 testing images and their labels.

https://mega.nz/file/MgVhQSoS#kOcuJFezOwU_9F46GZ1KJnX1STNny-tlD5oaJ9Hv0gY

## Building the Project

Our project is built on a foundation of cutting-edge technologies:

- YOLO v5: For real-time object detection, identifying signs of fire in live video feeds.
- Flask: To create a web interface that users can interact with to monitor alerts and manage the system.

Front End

![f1](https://github.com/adiimated/FireWatch/blob/main/media/f1.jpeg)

![f2](https://github.com/adiimated/FireWatch/blob/main/media/f2.jpeg)


## Client-Side Requirements
- Cloud Services: For data storage, analysis, and scalability. Ex: AWS and Google Cloud
- Hardware: Utilizing cameras capable of feeding data into our AI model.

Each component was carefully selected and integrated to ensure maximum efficiency and reliability.

## Challenges Faced

The road to development was not without its hurdles. Some of the challenges we encountered included:

- Data Collection: Gathering a sufficient amount of varied, high-quality data to train our model was a significant task.
- Model Training: Optimizing YOLO v5 to accurately detect fire without false positives required extensive testing and tuning.
- System Integration: Ensuring all components of our system communicated smoothly was a complex process.
- User Experience: Developing a user interface that was intuitive and simple, to balance the complex underlying working.

Despite these challenges, our dedication to creating a system that could make a real difference in the world keeps us pushing forward.


## Work Flow Diagram


![ubhacking](https://github.com/adiimated/FireWatch/blob/main/media/workflow.png)



