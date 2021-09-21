
Mask Wearing - v1 Mask Wearing-yolov5
==============================

This dataset was exported via roboflow.ai on September 21, 2021 at 5:33 PM GMT

It includes 359 images.
People are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 128x128 (Stretch)
* Auto-contrast via contrast stretching

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 60 percent of the image
* Random rotation of between -5 and +5 degrees
* Random shear of between -5° to +5° horizontally and -5° to +5° vertically
* Random brigthness adjustment of between -25 and +25 percent
* Random exposure adjustment of between -10 and +10 percent
* Random Gaussian blur of between 0 and 1 pixels

The following transformations were applied to the bounding boxes of each image:
* Random exposure adjustment of between -25 and +25 percent


