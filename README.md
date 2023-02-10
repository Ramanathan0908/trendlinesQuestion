# trendlinesQuestion

## The problem: 
Capturing and processing biodata in the real world is noisy and tedious. Describe a DL /AI architecture, algorithm, framework, bioinformatics approach, protocol, method, or approach you would take to process and extract human gaze from a camera.


I would first detect the eyeballs from the camera image (by using the difference in RGB gradient between the eyeballs and skin). The I would bound that region and within that region I would find the iris (by once again using the difference in RGB gradient between the eyeballs and Iris this time). Once I get these two information, I would compute the same information in the next frame and track the relative difference in the iris region (by comparing the coordinates of choosen anchor points) to get a direction vector for the motion of the iris!
