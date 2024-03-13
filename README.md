
# GestureWave: Hands-Free Human-Computer Interaction 

Virtual Gesture Interface: Streamlined Human-Computer Interaction Through Hand Gestures and Voice Commands. This innovative system enables users to control their computers without physical contact, utilizing advanced Machine Learning and Computer Vision technologies to interpret both static and dynamic hand gestures alongside voice commands. Leveraging cutting-edge algorithms like CNN implemented through [MediaPipe](https://github.com/google/mediapipe) and pybind11, the platform seamlessly integrates two modules: one focusing on direct hand detection using MediaPipe Hand detection, and the other utilizing gloves of any consistent color. Currently compatible with Windows platforms, this project eliminates the need for additional hardware while providing intuitive control over input/output operations

Note: Use Python version: 3.8.5


# Features

### Gesture Recognition:
<details>
<summary>Neutral Gesture</summary>
 <figure>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>
 

<details>
<summary>Move Cursor</summary>
  <figcaption>Cursor is assigned to the midpoint of index and middle fingertips. This gesture moves the cursor to the desired location. Speed of the cursor movement is proportional to the speed of hand.</figcaption>
</details>

<details>
<summary>Left Click</summary>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click</summary>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click</summary>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Scrolling</summary>
 <figcaption>Dynamic Gestures for horizontal and vertical scroll. The speed of scroll is proportional to the distance moved by pinch gesture from start point. Vertical and Horizontal scrolls are controlled by vertical and horizontal pinch movements respectively.</figcaption>
</details>

<details>
<summary>Drag and Drop</summary>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

<details>
<summary>Multiple Item Selection</summary>
 <figcaption>Gesture to select multiple items</figcaption>
</details>

<details>
<summary>Volume Control</summary>
 <figcaption>Dynamic Gestures for Volume control. The rate of increase/decrease of volume is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

<details>
<summary>Brightness Control</summary>
 <figcaption>Dynamic Gestures for Brightness control. The rate of increase/decrease of brightness is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>
