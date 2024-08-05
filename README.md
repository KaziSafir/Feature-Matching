# Feature-Matching
Using python I created a script script for feature matching between two images using different methods: ORB, SIFT, and FLANN. 

# Part 1: Load and Display Images:
Load two images (kitkat.jpg and chocolates.jpg) in grayscale using OpenCV, and display them using Matplotlib.

# Part 2: ORB Detection and Matching:

Detect keypoints and compute descriptors using the ORB detector.

Match descriptors using the Brute Force Matcher with Hamming distance.

Sort matches based on the distance and display the top 50 matches.

# Part 3: SIFT Detection and Matching:

Detect keypoints and compute descriptors using the SIFT detector.

Match descriptors using the Brute Force Matcher and apply a ratio test to filter good matches.

Display the top 50 matches.

# Part 4: FLANN-based Matching:

Use FLANN (Fast Library for Approximate Nearest Neighbors) for matching descriptors.

Apply a ratio test to filter good matches and display them.

# Note:

Ensure that the images (kitkat.jpg and chocolates.jpg) are available in the working directory, or provide the correct paths to them.
