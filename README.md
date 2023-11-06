# Fire Detection


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

![f1](https://github.com/UBH-Fall2023/ubh-fall2023-adiimated/assets/56118819/60bd7630-09cb-4255-aec4-96a0c862f50b)

![f2](https://github.com/UBH-Fall2023/ubh-fall2023-adiimated/assets/56118819/5d423168-ebb5-4a19-8cb1-f54074e1de19)


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


![ubhacking](https://github.com/UBH-Fall2023/ubh-fall2023-adiimated/assets/56118819/c841c036-0c3c-46ab-b6c8-820b9ecc5ab9)



# UB Hacking Fall 2023 Rules 
- Teams can consist of between 1 and 4 people.
- To have your submission be considered for judging, you must submit a 2-5 minute video along with your project. Try to keep it as concise as possible!
- The projects submitted for judging cannot have been started prior to the start of the hackathon. In other words, teams can plan their projects in great detail, but they cannot begin writing code until they arrive at the hackathon.
- Additionally, we are partnering with MLH this year, which means that our hackers must follow their code of conduct which can be found below.
- Any and all resources used must be open source and specified in either the project, or the project description.
- Your project must be publically available and under source control in this repository.
- Prior to submitting to devpost, your project must be fully committed and pushed to this repository.
- The link to this repository must be available on your devpost submission.
- Projects can not have been submitted to another event, including other hackathons this weekend.
- [Code of Conduct](https://drive.google.com/file/d/1RH_TtRu6EOHSbOoiSj2h1Q4jswtVILzE/view)
- [MLH Code of Conduct](https://static.mlh.io/docs/mlh-code-of-conduct.pdf)
