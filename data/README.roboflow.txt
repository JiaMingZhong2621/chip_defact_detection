
Aerial Airport - v1 v1
==============================

This dataset was exported via roboflow.ai on August 11, 2021 at 5:45 AM GMT

It includes 810 images.
Planes are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 600x600 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 30 percent of the image
* Random brigthness adjustment of between -20 and +20 percent
* Random exposure adjustment of between -10 and +10 percent


