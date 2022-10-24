# Overview

This repo contains URDF files for the humanoid robot TOCABI. Additionally, we provide a USD file for use in NVIDIA Omniverse.

![image](https://user-images.githubusercontent.com/11399119/196281096-3ab2740f-f79f-4201-a8dc-6e05649bec24.png)


## Files

There are two folders: "combined" is the robot with one `.stl` file per link, as typically provided for robots.  To provide a closer model to creating a digital twin, the "subbodies" folder uses the "visual" component of URDF with each part as its own `.stl`, and a single link `.stl` as a collision body. 

The USD file has materials applied, the robot joints configured, and ready for simulation. Since the USD file is large,  we provide access through a google drive link [USD Link](https://drive.google.com/file/d/140kFxSP2MdZzfkZI8gcKiwrGgeiVN2wT/view?usp=sharing). 

## Downloading

This repo uses gitlfs. Since there isn't much in the way of code, the easiest way to download is clicking `code` on the github website and downloading as a zip.

## Generating Files

The URDF files were created with our FusionDescriptor (https://github.com/cadop/fusion360descriptor) plugin for Fusion360.  You can use that for your own robots. We then used NVIDIA Omniverse Create and added the isaacsim URDF workflow to convert to our USD file. 

## Issues

If you have any issues with using the URDF or USD file, please open an issue on github.  If you would like to discuss anything or have general questions, please use the discussions tab. 
