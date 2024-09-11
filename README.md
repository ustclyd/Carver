# Carver
a repo for Carver: Learning to Reconstruct Right Ventricle from Sparse Multi-View 2D Echocardiograms

![image](https://github.com/ustclyd/Carver/blob/main/fig1-wzh.drawio.png)

## Get Data

We constructed a clinical echocardiogram dataset collected from The Ultrasonic Department of The First Affiliated Hospital of USTC. This dataset contains 1,278 samples in different heartbeat cycles from 32 patients. This dataset is private.


## Make Dual-channel Dataset

Using files in ./Dataset & ./Dual_data_maker to construct dual-channel data from original datast.

## Set configs

Set configs in ./config.py. Choose the model in ./model.py.

## Run
Run ./run.py to run the code. 
Type --help to see helps.
