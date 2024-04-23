# FMCW LiDAR Object Detection Dataset
FMCW LiDAR Point Cloud of object detection dataset based on CARLA, FMCWLidDet.

Building FMCW LiDAR sensors in CARLA and collecting data.

Point cloud data contains three-dimensional coordinate information (x, y, z) and Doppler velocity information (v) of points.

## Dataset Structure
    FMCWLidDet_Dataset
    |
    |-- bags
    |    |-- Town 01.bag
    |    |-- Town 02.bag
    |    |-- ... 
    |-- pcds
    |    |-- 000001.pcd
    |    |-- 000002.pcd
    |    |-- ...
    |-- bins
    |    |-- 000001.bin
    |    |-- 000002.bin
    |    |-- ...
    |-- labels
    |    |-- 000001.txt
    |    |-- 000002.txt
    |    |-- ...
    |-- ImageSets
       |-- train.txt
       |-- val.txt
       |--test.txt

## Algorithm architecture configuration
Based on the OpenPCDet algorithm framework. Configuration file required:

(1) pcdet -> datasets -> fmcw -> fmcw_dataset.py

(2) 

