## Hand Gesture Based Electric Appliance Controller

The Hand Gesture-Based Electrical Appliance Control System is a computer vision and embedded automation project designed to control electrical appliances through real-time hand gestures without requiring physical switches or remote controls. The system uses Python, OpenCV, and Google's MediaPipe Hands library to recognize predefined hand gestures and translate them into control commands for switching electrical appliances.

## Working Principle and Implementation

The system uses a webcam to continuously capture video frames of the user's hand. OpenCV handles video acquisition, image processing, and frame manipulation, while MediaPipe performs real-time hand detection and landmark tracking. MediaPipe identifies 21 key landmarks on the human hand, including fingertips and finger joints. The relative positions of these landmarks are analysed to determine which fingers are extended and classify the corresponding hand gesture.

Each recognized gesture is mapped to a predefined electrical appliance control command. The generated commands are communicated to the embedded controller, which operates the connected electrical appliances through relay-based switching circuits. This enables users to control devices such as lights, fans, and other compatible electrical loads using simple hand movements.

<img width="729" height="422" alt="image" src="https://github.com/user-attachments/assets/ffc56a01-4fe1-410c-a861-b5f971524478" /> <img width="515" height="444" alt="image" src="https://github.com/user-attachments/assets/614173d1-ede3-407d-80be-063837c12aae" />

<img width="1255" height="709" alt="image" src="https://github.com/user-attachments/assets/3138665d-b2d9-45de-9729-bc638e303c1b" />
<img width="1179" height="681" alt="image" src="https://github.com/user-attachments/assets/0469c892-f3d3-46ea-aef4-dba90c3a7e92" />


## Technology and Applications

The project integrates Python programming, OpenCV-based image processing, MediaPipe machine learning models, gesture recognition algorithms, and embedded hardware interfacing. The system provides a touchless human-machine interface that eliminates dependency on conventional mechanical switches and improves convenience in electrical appliance operation.

The solution has potential applications in smart home automation, assistive technology for individuals with limited mobility, industrial control interfaces, and contactless electrical switching systems.

Overall, this project demonstrates the integration of computer vision, artificial intelligence, and embedded electronics to develop an intuitive electrical appliance control solution. It provides a foundation for advanced smart automation systems with opportunities for future expansion through IoT connectivity, wireless appliance control, voice integration, and mobile application-based monitoring.
