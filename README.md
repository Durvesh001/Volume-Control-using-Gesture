# Hand Gesture Volume Control
This project utilizes computer vision and hand gesture recognition techniques to control the system volume using hand movements. By detecting the position of the thumb and index finger, the program calculates the distance between them and maps it to the system volume range. The volume level is then adjusted accordingly.

## Technologies Used
- Python
- OpenCV: Used for capturing video from the camera and processing frames.
- MediaPipe: Utilized for hand detection and landmark estimation.
- PyCaw: Used to control the system volume.
- NumPy: Used for interpolation and mapping calculations.

### Results Achieved
This project successfully allows the user to control the system volume using hand gestures. The program captures video from the camera and applies hand detection to identify the landmarks of the hand, specifically the thumb and index finger. By calculating the distance between these landmarks, the script maps it to the system volume range and adjusts the volume accordingly.
The volume control is visualized through a graphical bar that represents the volume level. Additionally, the program displays the volume percentage on the screen.

#### Future Enhancements
1. Implement more hand gestures for additional functionalities such as play/pause, skip, or mute.
2. Improve the accuracy and robustness of hand detection and tracking.
3. Add support for multiple hands and multi-gesture recognition.
4. Create a graphical user interface (GUI) for a more user-friendly experience.

5. Representation of working Code -
6. ![image](https://github.com/Durvesh001/Volume-Control-using-Gesture/assets/75305014/522cb91d-b3f2-46f2-902a-0decf1b483b8)
![image](https://github.com/Durvesh001/Volume-Control-using-Gesture/assets/75305014/5dbe0d14-0ef4-49f1-b7e5-df93d0dd563e)

