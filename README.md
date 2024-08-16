This repo is a private fork of Groundingdino trying to get Docker to run for my system.
The original repo is found here: https://github.com/IDEA-Research/GroundingDINO

Build Docker: sudo docker build -t groundingdino . 

Run Docker with Nvidia Gpus and the NVIDIA Container Toolkit installed: sudo docker run --rm --gpus all -p 8080:80 groundingdino
