Traffic Violation Detection System
Overview
This project focuses on the development of a comprehensive Traffic Violation Detection System, integrating machine learning, mobile development, and cloud computing. The system employs a computer vision approach to automatically detect traffic violations in Advanced Traffic Control System (ATCS) CCTV footage.

Machine Learning
Object Recognition
Four YOLO models have been trained to recognize crucial objects in the CCTV footage, including vehicles, helmets, seatbelts, and license plates. These models collaborate to identify traffic violations such as riding without a helmet or unbuckled seatbelts.

Optical Character Recognition (OCR)
A ResNet model has been implemented for optical character recognition on license plates, extracting essential information for further processing.

Workflow
Upon detection of a violation, the system extracts relevant information such as license plate number, violation type, location, violation image, and event timestamp. This information is then transmitted to the backend server via a REST API.

Mobile Development
UI/UX Design
Meticulous UI/UX design in Figma laid the foundation for a truly intuitive user experience. The Android app, built with Jetpack Compose, incorporates customized components for optimal clarity and engagement.

User-Centric Design
Valuable UI/UX advisor feedback further refined the interface, ensuring seamless navigation and effortless data capture.

Integration
The app seamlessly integrates with the REST API, facilitating real-time data exchange. This integration completes the app's core functionality, providing users with a responsive and intuitive experience.

Cloud Computing
Machine Learning Model Deployment
The machine learning model is successfully deployed, and a robust backend server infrastructure is established. Express.js serves as the pivotal framework, connecting the machine learning model, Android application, and database components.

Data Storage
MySQL is employed for the efficient storage of text-based data, while image files are securely housed within cloud storage. Cloud SQL and Cloud Storage from Google Cloud Platform (GCP) are utilized for comprehensive application management.

API Deployment
The API deployment encompasses two distinct types: a backend API crafted in Node.js, and a machine learning API implemented using Flask. Application data is meticulously organized within Cloud SQL utilizing a MySQL database.

Security and Scalability
This meticulously designed configuration fosters efficient application management, concurrently guaranteeing the security and scalability of the stored data.

Deployment
The system is deployed on Cloud Run, leveraging both PyTorch and TensorFlow models for efficient inference and communication with the backend server. This robust architecture ensures smooth performance and future feature expansion, ensuring the app remains relevant and valuable for users.
