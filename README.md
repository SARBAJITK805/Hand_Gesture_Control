# Hand Gesture Control for Media Playback & Volume Adjustment

This Python script uses OpenCV and MediaPipe to recognize hand gestures and control media playback (play/pause) and system volume using a webcam.

## Features
- **Play/Pause Media**: Control media playback using wrist and middle finger positioning.
- **Adjust Volume**: Change system volume by pinching your thumb and index finger.
- **Real-time Hand Tracking**: Uses MediaPipe Hands for gesture detection.
- **Visual Feedback**: Displays bounding boxes and interaction elements on the screen.

## Prerequisites
Ensure you have Python installed and install the required dependencies using:

```sh
pip install opencv-python mediapipe python-vlc numpy pycaw
```

## How It Works
1. **Media Playback Control**:
   - Move your hand inside the designated "Play/Pause Controller" box.
   - Stretch your wrist and middle finger apart to play the video.
   - Bring them close together to pause it.
2. **Volume Control**:
   - Move your hand inside the "Volume Controller" box.
   - Pinch your thumb and index finger to adjust volume.
   - The closer they are, the lower the volume; the farther, the higher.

## Usage
Run the script using:

```sh
python hand_gesture_control.py
```

### Controls:
- **Play/Pause**: Open and close hand in the designated region.
- **Adjust Volume**: Move thumb and index finger closer or farther apart.
- **Exit**: Press 'q' to quit the application.

## Dependencies
- OpenCV
- MediaPipe
- VLC
- Pycaw (for audio control)
- NumPy

## Notes
- Ensure your webcam is functional.
- Adjust detection confidence levels if needed.
- Works best in good lighting conditions.

## License
This project is open-source and available under the MIT License.

