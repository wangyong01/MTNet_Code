# MTNet, a deep generative model for trajectory modeling and utilization.

We present the core source code of MTNet in the zip file.

The audience can directly run train.py to see a trajectory data modeling demo on the Chengdu road network.

The learned model can be used to generate representative trajectories by calling the sampling method of MTNet.

## Directory layout

    .
    ├── train                 # MTNet model training demo entrance
    ├── mtnet                 # MTNet model structure and details 
    ├── data                  # Data files, e.g., roads and trajectories
    ├── util/config           # Global config settings 
    ├── util/mtnet.yaml       # MTNet model hyper-parameters 
    ├── util/dataloader       # Data loader and preprocessing 
    ├── utils/params          # The learned MTNet model
    └── utils/others          # Tools and utilities 
