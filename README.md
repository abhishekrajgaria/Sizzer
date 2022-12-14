# Sizzer - Cloth Size Predictor

An application to detect clothes size using image analysis.<br> An A4 size sheet is used as a reference.

## Requirements

- Python3
- Opencv
- imutils

## Installing

`sudo chmod a+x getModels.sh
./getModels.sh`

### How To Run

`python3 main.py --image src/<image_file_name> --width <size of A4 sheet(7.87)>`

## Aim

Main motive of the project is to take the image of any person and tell him the required size of the clothes he is looking for.

## Functionality

Project detects the dimensions of a human body required for the clothes sizes. It does that by detecting the dimensions of the reference A4 sheet and measuring them. Then, it recognises the location of joints in the picture and then calculates the distance between the joints with respect to the reference sheet. Then, using a pre-defined range, as per the clothes vendor, it tells the corresponding size.

![sizzer_methodology](https://user-images.githubusercontent.com/30906709/205591187-c01ed1df-fa3d-446f-8314-6f93995178c6.png)

## Authors

- Mohit Juneja
- Abhishek Rajgaria
- Gandharv Mohan
- Anshuman Singh
