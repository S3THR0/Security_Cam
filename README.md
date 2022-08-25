# LOGIN/REGISTER

STEP 0 : OPEN COMMAND LINE/ BE IN ACTIVE DIRECTORY

STEP 1 : RUN "pip install -r requirements.txt"

STEP 2 : RUN "python3 securitycam.py"

STEP 3 : TYPE "q" TO QUIT

STEP 4 : IF ON WINDOWS OPERATION SYSTEM & YOU WANT SOUN ALERT. OPEN "securitycam.py"
in a text editor, remove the # in line 2, & 21.

# Notes

In order to change camera source, via file, link or plug in,
look for line 5.

cam = cv2.VideoCapture(0)

replace the (0) with a different source such as file path
cam = cv2.VideoCapture("Videos/vid1.mp4)

or a different number a plugged in media
cam = cv2.VideoCapture(1)

cam = cv2.VideoCapture("websitelink:port")

there are many plans for the future, im aware this is not secure for production. this is my learn as i go project.
You may use this ontop of your own code.
