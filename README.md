# Memorability - Third year University project

A project supervised by Dr. Adrian Bors, titled "Computer Learning of what is Memorable from Images", where I explored the use of CNNs to predict the most and least memorable regions of images.

I explored several deep learning techniques and settled on Transfer Learning, which I implemented in PyTorch.

This project contained Visual Memory Schema (VMS) like the following, which show the most memorable regions of images.

![sample_vms_greyscale](https://user-images.githubusercontent.com/73166823/205845892-32944b7a-1a6a-433d-81a2-3cd38f7d0f8e.png)

![sample_vms_overlayed](https://user-images.githubusercontent.com/73166823/205845838-d3939277-c3f0-46d7-9936-a78bdbfeb8ad.png)

I attempted to train a CNN to generate such VMS, with disappointing results, but the experience I gained about Transfer Learning and the deep knowledge of PyTorch and general Python while doing this project was more valuable than any results I could've hoped for.

A sample of "good" VMS maps I managed to generate are shown below (Top are generated, bottom are actual VMS maps from the dataset).

![best_vms](https://user-images.githubusercontent.com/73166823/205846645-07279ebd-4e87-4599-b5fb-a40dd6c7a607.png)
