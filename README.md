# hand-gesture-recognition-using-mediapipe

# Requirements
1)opencv-python
2)mediapipe


# MediaPipe

Simple Hand Gesture Recognition Code - Hand tracking - Mediapipe
Goal of this gist is to recognize B(baby fingure), T(thumb), M(middle),  R(ring fingure), I(index fingure). We use the LANDMARKS output of the Landmark. This output is a landmark list that contains 21 landmark. In the hand_landmarks.jpg picture below you can see the index of each landmark. Each landmark have x, y and z values. But only x, y values are sufficient for our Goal.
We have five finger states.
thumbIsOpen
firstFingerIsOpen
secondFingerIsOpen
thirdFingerIsOpen
fourthFingerIsOpen
For exmaple: thumb is open if the x value of landmark 3 and the x value of landmark 4 are less than x value of landmark 2 else it is close
![hand_landmarks](https://user-images.githubusercontent.com/82312119/189110203-ba05c301-5db1-481e-9b97-c42f0b686926.png)

![hand_crops](https://user-images.githubusercontent.com/82312119/189110520-93bdc9c5-24cf-4493-acb1-d36d75e7bc35.png)

# Reference
MediaPipe
https://google.github.io/mediapipe/solutions/hands.html

