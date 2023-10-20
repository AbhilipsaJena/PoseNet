# PoseNet with p5.js
This is a simple p5.js sketch that uses the PoseNet machine learning model to detect key body points in a video feed and draw them on the canvas. It highlights the nose, right eye, and left eye positions with ellipses and draws skeletal connections between the key points.

### Getting Started
Clone or download this repository to your local machine.

Open the index.html file in a web browser.

### Dependencies
This project relies on the following libraries:
p5.js: A JavaScript library for creative coding.

ml5.js: A library that simplifies working with machine learning models in JavaScript.

These libraries should be included in the HTML file.

### How to Use
When you open the application, you should see a webcam video feed on the canvas.

The PoseNet model will detect key body points, such as the nose, right eye, and left eye.

The positions of these points are drawn as ellipses on the canvas.

Skeletal connections between key points are drawn using lines.
