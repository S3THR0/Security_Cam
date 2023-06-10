# LOGIN/REGISTER

## Setup Instructions

1. Open the command line and navigate to the active directory.

2. Run the following command to install the required dependencies:
```
pip install -r requirements.txt
```

3. Run the security camera application by executing the following command:
```
python3 securitycam.py
```

4. To quit the application, simply type "q" in the command line.

## Windows Operating System Sound Alert (Optional)

If you are using a Windows operating system and wish to enable sound alerts, follow these steps:

1. Open the "securitycam.py" file in a text editor.

2. Remove the "#" character from lines 2 and 21.

## Changing Camera Source

To change the camera source, whether from a file, link, or plugged-in device, follow these instructions:

1. Locate line 5 in the "securitycam.py" file:
```
cam = cv2.VideoCapture(0)
```

2. Replace the "0" parameter with the desired source, such as:
   - For a file path: `cam = cv2.VideoCapture("Videos/vid1.mp4")`
   - For a plugged-in device: `cam = cv2.VideoCapture(1)`
   - For a web URL with port: `cam = cv2.VideoCapture("websitelink:port")`

## Important Note

Please be aware that this project is a personal learning endeavor and is not suitable for production use as it lacks security measures. You are encouraged to use this codebase alongside your own to enhance its functionality.

Feel free to incorporate this into your existing codebase and make necessary modifications.

If you have any questions or run into any issues, feel free to reach out to me.