# Description

Neural Network training with **'DarkMark'**, **'Darknet'** based **'yolov4-tiny'** architecture with resources of **'OMiLab'** at the **'university of Vienna'**. Operating system is **'ubuntu'**. It has been defined 3 scenarios called Net1, Net2 and Net3 with different options to compare them at the end.
It also has been used server on computer in OMiLab with camera in this laboratory.

## Domain

Domain was Smart city objects. It has been used 6 default objects and 4 extra objects and in total 10 classes to train the network.

## Net1

In first scenario neutwork has been traind with this congifuration:

    - `batch_size` = 64
    - `sub_division` = 8
    - `max_batch` = 4000

Mosaic and flip left and right were the techniques used for augmentation.
Labeling data has been done with DarkMark. At the end of training it has been used 3 file extensions made by DarkNet to test: .names, .cnf, .weights .

It took **14 min** to train.

## Net2

In first scenario neutwork has been traind with this congifuration:

    - `batch_size` = 32
    - `sub_division` = 8
    - `max_batch` = 4000

Cutmix and flip left and right were the techniques used for augmentation.
Labeling data has been done with DarkMark. At the end of training it has been used 3 file extensions made by DarkNet to test: .names, .cnf, .weights .

It took **7.28** min to train.

## Net3

In first scenario neutwork has been traind with this congifuration:

    - `batch_size` = 128
    - `sub_division` = 8
    - `max_batch` = 4000

Random corp and image zoom and tile images were the techniques used for augmentation.
Labeling data has been done with DarkMark. At the end of training it has been used 3 file extensions made by DarkNet to test: .names, .cnf, .weights .

It took **26.09** min to train.
