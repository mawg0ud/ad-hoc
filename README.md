
# Wireless Sensor Network Simulation

This repository presents a research paper and MATLAB code for optimizing wireless sensor networks using a fixed topology and threshold-based analysis.

## Research Paper

### Title: 
QoS Provision for Controlling Energy Consumption in Ad-hoc Wireless Sensor Networks

### Date Published: 
10/12/2021

### Code Published: 
19/6/2022

### Language: 
Matlab
   
### Paper Link:
- Arxiv Version: https://arxiv.org/abs/2001.02761v1
- Journal Version: http://www.icicel.org/ell/contents/2020/8/el-14-08-03.pdf

#### Abstract:

Ad-hoc wireless sensor network is an architecture of connected nodes; each node has its main elements such as sensors, computation and communications capabilities. Ad-hoc WSNs restrained energy sources result in a shorter lifetime of the sensor network and inefficient topology. In this paper, a new approach for saving and energy controlling is introduced using quality of service. The main reason is to reduce the node’s energy through discovering the best optimum route that meets QoS requirements; QoS technique is used to find the optimum methodology for nodes packets transmission and energy consumption. The primary goals of the research are to discover the best techniques to: 
1) Minimize the total consumed energy in the ad hoc wireless sensor network.
2) Maximize the ad hoc wireless sensor network lifetime. The simulations of the problem will be formulated with the use of Integer Linear Programming.
   
#### Introduction

Ad-hoc wireless sensor networks are decentralized networks lacking a base station infrastructure, relying on nodes to act as hosts and routers. These networks utilize multi-hop communication, where data packets are relayed through intermediate nodes. The components of a sensor node typically include radio, battery, microcontroller, analog circuit, and sensor interface.

#### Problem Statement

The need to optimize energy consumption in ad-hoc WSNs by controlling transmission energy levels. Topology control plays a crucial role in assigning energy resources to transceivers, ensuring efficient communication while minimizing energy consumption.

#### Solution Methodology

The proposed solution leverages the decentralized nature of ad-hoc WSNs and employs optimization techniques to enhance network performance and energy efficiency. Quality of Service (QoS) parameters such as battery lifetime, bandwidth, and network availability are considered to ensure deterministic network behavior.

#### Experimental Section

Simulations were conducted to evaluate the effectiveness of the proposed approach. The experiments aimed to establish the relationship between QoS parameters, energy consumption, and network stability. Results demonstrate the impact of threshold values and traffic loads on network performance and energy consumption.

## MATLAB Code

The MATLAB code within this repository implements the methodologies detailed in the research paper. The primary script, `ex2.m`, serves as a practical demonstration of the optimization process for wireless sensor networks. It utilizes a fixed topology generated by `topology_generation3.m` and the `reqBank4` function to generate request data.
  

### Getting Started

1. Clone the repository to your local machine.

```bash

git clone https://github.com/mawg0ud/Wireless-Sensor-Networks-Simulation/
```


## Contribution Guidelines

We welcome contributions to this project. If you wish to contribute, please adhere to the following guidelines:

1. Fork the repository.
2. Create a new branch.
3. Implement your contributions.
4. Submit a pull request.



## License

This project is licensed under the [MIT License](LICENSE).
