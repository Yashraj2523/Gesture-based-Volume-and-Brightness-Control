# Hand Gesture-Based Volume and Brightness Control

## Overview
This Python project enables users to control system volume and screen brightness using hand gestures. It utilizes the **MediaPipe** library for hand tracking, **OpenCV** for computer vision, and **pycaw** and **screen_brightness_control** to manage audio and brightness levels, respectively.

## Features
- **Adjust Volume**: Move your right-hand index and thumb closer or apart to control system volume.
- **Adjust Brightness**: Move your left-hand index and thumb closer or apart to control screen brightness.
- **Exit Gesture**: Touch both thumbs together to exit the program.

## Requirements
Ensure you have the following dependencies installed:

```sh
pip install opencv-python numpy mediapipe screen-brightness-control pycaw comtypes
```

## How It Works
1. **Hand Tracking**: Uses MediaPipe to detect hands and track landmarks.
2. **Distance Calculation**: Calculates the distance between the index finger and thumb for both hands.
3. **Volume Control**: The right-hand gesture modifies system volume.
4. **Brightness Control**: The left-hand gesture modifies screen brightness.
5. **Exit Condition**: Bringing both thumbs together exits the program.

## Usage
Run the script using:

```sh
python script_name.py
```

### Controls
- **Increase/Decrease Volume**: Move the right index finger and thumb closer or apart.
- **Increase/Decrease Brightness**: Move the left index finger and thumb closer or apart.
- **Exit Program**: Touch both thumbs together.

## File Structure
- `script_name.py` - Main script implementing hand tracking and gesture control.

## Troubleshooting
- Ensure your webcam is properly connected.
- Run the script in a well-lit environment for better hand tracking.
- If brightness control doesn’t work, check system compatibility with `screen_brightness_control`.

## License
This project is open-source and available under the MIT License.

## Contributions
Feel free to fork the repository and submit pull requests for improvements or bug fixes!

