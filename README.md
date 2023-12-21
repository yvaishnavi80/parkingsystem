# parkingsystem
To run:

python main.py --image images/parking_lot_1.png --data data/coordinates_1.yml --video videos/parking_lot_1.mp4 --start-frame 400
Program flow is as follows:

User inputs file name for a video, a still image from the video, and a path for the output file of parking space coordinates.
User clicks 4 corners for each spot they want tracked. Presses 'q' when all desired spots are marked.
Video begins with the user provided boxes overlayed the video. Occupied spots initialized with red boxes, available spots with green.
Car leaves a space, the red box turns green.
Car drives into a free space, the green box turns red.
The data on the entering and exiting of these cars can be used for a number of purposes: closest spot detection, analytics on parking lot usage, and for those counters outside of parking garages that tell you how many cars are on each level (to name a few).
