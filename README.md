# HandGestures
Youtube Automation using Hand Gestures

Want to play/pause on Youtube and hands are dirty/occupied? No problem. This simple algorithm uses background reduction and motion detection to detect your hand in a given frame. For now it can only Play/Pause using PyAutoGUI by pressing the spacebar automatically.


Segment.py detects your hand or any other object as soon as it enters the green frame and pushes the spacebar once. Then after you remove it from the frame and place it back in the frame, it will detect it again and push the spacebar again.


Recognize.py on the other hand, also detects how many fingers you have held up inside the frame. This however is a bit worse than a drunk man in detecting them. This is like an extension of segment.py and it's sole purpose was to detect fingers. I built up on this and segment.py and added the automation. Please do experiment on them!
Make sure to have a stationary and clear background.
