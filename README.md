# CMU-Mo-Cap-Pose-Library
This project is an attempt to clean up the CMU Mo-Cap Library of bvh files found here: http://www.cgspeed.com/2014/06/interim-files-listing-part-5-updated.html

I've created a template blender file, with a base character added, which unfortunately is too large to upload to Github (which has a max file size of 25 megabytes) except as a zip file. 

I'm in the process of loading the bvh files, 1 per blender file, in the format ##-## v1.zip.
I intend to skip any files that are simply a t-pose, or otherwise too short to bother with. If a zipped blend file exceeds the Github 25-MB limit, I will post a cleaned bvh file instead of a Blender file (to minimize duplication of effort, I will not post the raw .bvh files available at the link above).

The basic idea is to provide a raw file for each of the bvh files.

Anyone who wishes to participate in this project may make corrections to the animation, such as cleaning up any issues with hands or major bones, cleaning the animation to remove frames that are too close together, correcting any blatant errors of body parts colliding with themselves. Export the animation to a revised .bvh file.

The basic framework is

##-## v1.bvh for files that have been cleaned and major bone issues.

##-## v#[description].bvh to allow for different approaches to further enhancing the animation.

This project is an excellent opportunity to practice animation skills, and gain experience correcting data errors. There are over 2500 raw bvh files, so there are many from which to choose.

Ideally, a data scientist will be able to develop a script to automate the process of cleaning these animations.

The goal is to provide a convenient library of poses and animations that can be easily used with a wide range of 3D characters.

I'm basing this repository off the https://github.com/animate1978/MB-Lab MB-Lab github repository, to serve as a complement to that project.

Thank you.
