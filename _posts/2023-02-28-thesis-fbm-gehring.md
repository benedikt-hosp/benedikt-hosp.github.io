---
title: Thesis on Detection and tracking of soccer players in 360 degree videos for automatic AOI generation.
date: 2023-02-28 17:20:00 +/-TTTT
categories: [Thesis]
tags: [thesis, done]     # TAG names should always be lowercase
---


Object tracking has long been an established area of research in computer vision.
 The objective is to identify objects in a video and track their location while maintaining 
 a given identity for the duration of their visibility. Applications can be found in many practical areas, 
 such as surveillance technology, autonomous driving, or animal and bacterial behavior studies. Typically, 
 tracking is done on normal planar video. With the proliferation of VR headsets and cameras capable of capturing 360° 
 images, tracking 360° videos is now becoming the research focus. This work fits into a larger project in this regard.
 The goal is to analyze what is paid attention to when viewing a training situation in soccer. Part of this work tracks 
 the players' movements through the video. In other projects, a VR headset is being designed with sensors built into it 
 that can be used to determine the direction of gaze and, thus, what point in the video is being looked at. Together with
 the data from the tracking, it is possible to automatically analyze which player was paid particular attention to. It is 
 hoped that this will provide insights into sports science. Such techniques could also be used in the user interface area, 
 for example, to automatically provide information about interesting players and objects or to enable interaction possibilities 
 in virtual reality. 

This work investigates the tracking of soccer players in training situations. A moving cameraman 
filmed the scenes with a camera located on his shoulders. Both the automation of this process and the 'detection based tracking' 
approach make object detection on these videos, respectively on the individual frames, necessary for this purpose. 
For this reason, the investigation of object detectors and techniques for object detection on these videos is just 
as necessary as that of trackers. For object detection, it will be discussed whether the approaches that already exist 
for this purpose on omnidirectional images can be transferred to the present training scenes. For tracking, different 
trackers developed for planar videos will be applied to the training scenes, and their performance will be compared.
 From this, one can deduce what approach a tracker developed specifically for such training scenes should take. Thus, 
 the question of what is the optimal approach for tracking soccer players in 360◦ videos is investigated. In the practical 
 part, a simple tracker prototype is designed, which once implements the whole workflow, i.e., detection, tracking, 
 and output of the data, for videos in Equirectangular Panorama format. This is also compared with the other trackers 
 and shows the peculiarities of tracking on these videos.