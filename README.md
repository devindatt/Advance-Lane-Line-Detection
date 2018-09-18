{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Advanced Lane Detection\
===\
In this Advanced Lane Detection project, we apply computer vision techniques to augment video output with a detected road lane, road radius curvature and road centre offset. The video was supplied by Udacity and captured using the middle camera.\
\
<a href="https://imgflip.com/gif/2i68ue"><img src="https://i.imgflip.com/2i68ue.gif" title="made at imgflip.com"/></a>\
\
<a href="https://imgflip.com/gif/2i690l"><img src="https://i.imgflip.com/2i690l.gif" title="made at imgflip.com"/></a>\
\
The goals / steps of this project are the following:\
\
- Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.\
- Apply a distortion correction to raw images.\
- Use color transforms, gradients, etc., to create a thresholded binary image.\
- Apply a perspective transform to rectify binary image ("birds-eye view").\
- Detect lane pixels and fit to find the lane boundary.\
- Determine the curvature of the lane and vehicle position with respect to center.\
- Warp the detected lane boundaries back onto the original image.\
- Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.\
\
 The project is written in python and utilises [numpy](http://www.numpy.org/) and [OpenCV](http://opencv.org/).\
}