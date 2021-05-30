# Line-detection
# Overview
This Line detection module development is used to provided the location of welding seam with OpenCV. The further order will be activiate a robot movement.

It consist of four methonds, including line_detection, intersections, pinhole_model and locate_start_point. 
1. line_detection(image): detect the edges in images 
2. intersections(lines): locate the intersection
3. pinhole_model(x,y): project the point on image to the real world
4. locate_start_point(x,y): locate the start point to robot coordinate system

# Environment
Python 3 with OpenCV installed.
