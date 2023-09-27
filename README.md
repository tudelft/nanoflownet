# NanoFlowNet: Real-time Dense Optical Flow on a Nano Quadcopter
Code and trained networks of the paper "NanoFlowNet: Real-time Dense Optical Flow on a Nano Quadcopter"

## Publication
Nano quadcopters are small, agile, and cheap platforms that are well suited for deployment in narrow, cluttered environments. Due to their limited payload, these vehicles are highly constrained in processing power, rendering conventional vision-based methods for safe and autonomous navigation incompatible. Recent machine learning developments promise high-performance perception at low latency, while dedicated edge computing hardware has the potential to augment the processing capabilities of these limited devices. In this work, we present NanoFlowNet, a lightweight convolutional neural network for real-time dense optical flow estimation on edge computing hardware. We draw inspiration from recent advances in semantic segmentation for the design of this network. Additionally, we guide the learning of optical flow using motion boundary ground truth data, which improves performance with no impact on latency. Validation results on the MPI-Sintel dataset show the high performance of the proposed network given its constrained architecture. Additionally, we successfully demonstrate the capabilities of NanoFlowNet by deploying it on the ultra-low power GAP8 microprocessor and by applying it to vision-based obstacle avoidance on board a Bitcraze Crazyflie, a 34 g nano quadcopter. 

[arXiv preprint](https://arxiv.org/abs/2209.06918)

[IEEE-ICRA 2023 paper](https://ieeexplore.ieee.org/document/10161258)

Please cite us as follows:
```
@inproceedings{bouwmeester2023nanoflownet,
  title={Nanoflownet: Real-time dense optical flow on a nano quadcopter},
  author={Bouwmeester, Rik J and Paredes-Vall{\'e}s, Federico and De Croon, Guido CHE},
  booktitle={2023 IEEE International Conference on Robotics and Automation (ICRA)},
  pages={1996--2003},
  year={2023},
  organization={IEEE}
}
```

## Usage
Initialize all submodules with `git submodule update --init --recursive`
Review the respective repositories for further instructions
