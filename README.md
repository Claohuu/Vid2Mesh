# Vid2Mesh

## Project Overview

Vid2Mesh is a computer vision project focused on reconstructing 3D scenes and objects from input videos.

The project explores sparse-view 3D reconstruction techniques, with an emphasis on 3D Gaussian Splatting (3DGS) and realistic 3D representations.

## Project Goals

3D Object Reconstruction from Video. Develop a tool that takes a video of an object and creates a 3D mesh asset of that object using 3D Gaussian splatting. Pull detailed surface textures and colors from the video directly onto the 3D object, creating a game-ready asset without the use of traditional modeling software. We will implement a polygon budget, decimating the model to specific triangle limits while preserving the overall geometry.

We want to investigate how different factors in a video (lighting, quality, length) affect the reconstruction quality of the object into a 3D model. We will look into camera video viewpoint coverage, lighting conditions, and object characteristics like geometric complexity and texture. We will also compare our videometry-based reconstruction to traditional photogrammetry-based reconstruction to see how close we can get to the modern technology that’s used to create professional-tier games and animation.

## Milestones
- Week 1:  Create a repository in GitHub. Finish research. Build a keyframe selector from a video file as the source. Use algorithms (Laplacian Variance and Optical Flow) to discard blurry frames and save high-quality, sharp frames that overlap with other frames. Additionally, calculate the camera position in 3D space. 
- Week 2: 3D training with a computer vision framework, using 3D Gaussian Splatting to learn the 3D shape of the object.
- Week 3: Testing and experimenting with our implementation
Running our program with a bunch of different objects and images to adjust and fix bugs
Fully test with various lighting conditions to compare the reconstruction quality
- Week 4: Finished product and presentation
We can fully implement 3D object reconstruction based on videogrammetry
Compare and contrast the strengths and weaknesses of our approach and what we could’ve done better or did well.
- Stretch goal: We can have a feature to decrease the number of polygons on the 3D model for people who want to optimize their models for games, animation, and such.

## Project Structure

- TBD

## Setup

- TBD: considering website
