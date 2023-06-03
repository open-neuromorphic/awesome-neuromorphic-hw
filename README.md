# Awesome Neuromorphic Hardware [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

This repo collects papers, docs, codes about neuromorphic hardware for anyone who wants to do research on it. We are continuously improving the project. Welcome to PR the works (papers, repositories) that are missed by the repo. Inspired by [awesome-model-quantization](https://github.com/htqin/awesome-model-quantization).

- [Survey Papers](#Survey_Papers)
  
- [Papers](#Papers)
  - [2023](#2023) 
  - [2022](#2022)
  - [2021](#2021)
  - [2020](#2020)
  - [2019](#2019)
  - [2018](#2018)
  - [2017](#2017)
  - [2016](#2016)
  - [2015](#2015)
  - [2014](#2014)
  - [2013](#2013)
  - [2011](#2011)
  - [2010](#2010)
  
## Survey Papers

- [[ArXiv](https://arxiv.org/abs/2109.12894)] Training Spiking Neural Networks Using Lessons From Deep Learning, **2023**.
- [[ProcIEEE](https://arxiv.org/abs/2106.01288)] Bottom-up and top-down approaches for the design of neuromorphic processing systems: Tradeoffs and synergies between natural and artificial intelligence, **2023**.
- [[IEEE-CICC](https://arxiv.org/abs/2203.07006)] Spiking Neural Network Integrated Circuits: A Review of Trends and Future Directions, **2022**.
- [[ACM-JETCS](https://arxiv.org/abs/2005.01467)] Spiking Neural Networks Hardware Implementations and Challenges: a Survey, **2020**.
  
## Papers

### 2023

- [[ArXiv](https://arxiv.org/abs/2301.01905)] FireFly: A High-Throughput and Reconfigurable Hardware Accelerator for Spiking Neural Networks. [__`digital`__][__`fpga`__]
- [[IEEE-ISCAS](https://arxiv.org/abs/2302.01015)] OpenSpike: An OpenRAM SNN Accelerator. [__`digital`__][__`asic`__][__`open-source`__][[Code](https://github.com/sfmth/OpenSpike)]
- [[ArXiv](https://arxiv.org/abs/2212.01696)] THOR -- A Neuromorphic Processor with 7.29G TSOP2/mm2Js Energy-Throughput Efficiency. [__`digital`__][__`asic`__]
- [[IEEE-TCAD](https://ieeexplore.ieee.org/document/9785601)] The Implementation and Optimization of Neuromorphic Hardware for Supporting Spiking Neural Networks With MLP and CNN Topologies [__`digital`__][__`fpga`__]
- [[ArXiv](https://arxiv.org/abs/2304.06793)] Speck: A Smart event-based Vision Sensor with a low latency 327K Neuron Convolutional Neuronal Network Processing Pipeline. [__`digital`__][__`asic`__][__`async`__]
- [[ArXiv](https://arxiv.org/abs/2305.05187)] DeepFire2: A Convolutional Spiking Neural Network Accelerator on FPGAs. [__`digital`__][__`fpga`__]
- [[IEEE-JSSC](https://ieeexplore.ieee.org/abstract/document/10121702)] SNPU: An Energy-Efficient Spike Domain Deep-Neural-Network Processor With Two-Step Spike Encoding and Shift-and-Accumulation Unit. [__`digital`__][__`asic`__]
- [[IEEE-ISSCC](https://ieeexplore.ieee.org/abstract/document/10067497)] C-DNN: A 24.5-85.8TOPS/W Complementary-Deep-Neural-Network Processor with Heterogeneous CNN/SNN Core Architecture and Forward-Gradient-Based Sparsity Generation. [__`digital`__][__`asic`__]
- [[IEEE-CICC](https://ieeexplore.ieee.org/abstract/document/10121315)] A 22nm 0.43pJ/SOP Sparsity-Aware In-Memory Neuromorphic Computing System with Hybrid Spiking and Artificial Neural Network and Configurable Topology. [__`digital`__][__`asic`__][__`in-memory-computing`__]
- [[IEEE-ISCAS](https://www.linkedin.com/posts/bo-wang-114b17a0_shenjing-npu-activity-7064489906835787776-zroT?utm_source=share&utm_medium=member_desktop)] 1.7pJ/SOP Neuromorphic Processor with Integrated Partial Sum Routers for In-Network Computing. [__`digital`__][__`asic`__]
- [[IEEE-JSSC](https://ieeexplore.ieee.org/abstract/document/10130013)] Neuro-CIM: ADC-Less Neuromorphic Computing-in-Memory Processor With Operation Gating/Stopping and Digital–Analog Networks. [__`digital`__][__`asic`__][__`mixed-signal`__]
- [[IEEE-TCAS-II](https://ieeexplore.ieee.org/abstract/document/10129114)] Design of Time-Encoded Spiking Neural Networks in 7nm CMOS Technology. [__`digital`__][__`asic`__]
- [[ArXiv](https://arxiv.org/abs/2305.16187)] A tunable and versatile 28nm FD-SOI crossbar output circuit for low power analog SNN inference with eNVM synapses. [__`mixed-signal`__][__`memristive`__]
- [[IEEE-TBioCAS](https://ieeexplore.ieee.org/abstract/document/10132492)] A 510μW 0.738-mm2 6.2-pJ/SOP Online Learning Multi-Topology SNN Processor with Unified Computation Engine in 40-nm CMOS. [__`digital`__][__`asic`__]

### 2022

- [[IEEE-ISSCC](https://arxiv.org/abs/2208.09759)] ReckOn: A 28nm Sub-mm2 Task-Agnostic Spiking Recurrent Neural Network Processor Enabling On-Chip Learning over Second-Long Timescales. [__`digital`__][__`asic`__][__`open-source`__][[Code](https://github.com/chfrenkel/ReckON)]
- [[DATE](https://arxiv.org/abs/2204.10687)] SNE: an Energy-Proportional Digital Accelerator for Sparse Event-Based Convolutions. [__`digital`__][__`asic`__][__`open-source`__][[Code](https://github.com/pulp-platform/sne)]
- [[IEEE-TCAS-I](https://arxiv.org/abs/2205.00778)] Sparse Compressed Spiking Neural Network Accelerator for Object Detection. [__`digital`__][__`asic`__]
- [[IEEE-TCAD](https://arxiv.org/abs/2203.07516)] Skydiver: A Spiking Neural Network Accelerator Exploiting Spatio-Temporal Workload Balance [__`digital`__][__`fpga`__]
- [[IEEE/ACM-DAC](https://mxhx7199.github.io/files/[DAC-2022]SATO_preprint.pdf)] SATO: spiking neural network acceleration via temporal-oriented dataflow and architecture [__`digital`__][__`asic`__]

### 2021

- [[Frontiers](https://www.frontiersin.org/articles/10.3389/fnins.2021.664208/full)] μBrain: An Event-Driven and Fully Synthesizable Architecture for Spiking Neural Networks. [__`digital`__][__`asic`__]
- [[ArXiv](https://arxiv.org/abs/2103.08392)] The SpiNNaker 2 processing element architecture for hybrid digital neuromorphic computing. [__`digital`__][__`asic`__]
- [[IEEE-TCAS-I](https://ieeexplore.ieee.org/document/9546038)] A 5.28-mm² 4.5-pJ/SOP Energy-Efficient Spiking Neural Network Hardware With Reconfigurable High Processing Speed Neuron Core and Congestion-Aware Router. [__`digital`__][__`asic`__]
- [[IEEE-LSSC](https://arxiv.org/abs/2105.08217)] IMPULSE: A 65-nm Digital Compute-in-Memory Macro With Fused Weights and Membrane Potential for Spike-Based Sequential Learning Tasks. [__`digital`__][__`asic`__]
- [[IEEE-TVLSI](https://ieeexplore.ieee.org/document/9855834)] Cerebron: A Reconfigurable Architecture for Spatiotemporal Sparse Spiking Neural Networks [__`digital`__][__`fpga`__]
- [[ACM-TRTS](https://www.sfu.ca/~zhenman/files/C21-FPL2021-SyncNN.pdf)] SyncNN: Evaluating and Accelerating Spiking Neural Networks on FPGAs [__`digital`__][__`fpga`__][[Code](https://github.com/SFU-HiAccel/SyncNN)]
- [[IEEE-FPL](https://www.comp.nus.edu.sg/~wongwf/papers/FPL_2021_FINAL.pdf)] DeepFire: Acceleration of Convolutional Spiking Neural Network on Modern Field Programmable Gate Arrays [__`digital-FPGA`__]
- [[ACM-FPGA](https://dl.acm.org/doi/10.1145/3431920.3439283)] S2N2: A FPGA Accelerator for Streaming Spiking Neural Networks [__`digital`__][__`fpga`__]
- [[IEEE-TCAS-I](https://ieeexplore.ieee.org/document/9336327)] A Fast and Energy-Efficient SNN Processor With Adaptive Clock/Event-Driven Computation Scheme and Online Learning [__`digital`__][__`fpga`__]

### 2020

- [[IEEE-A-SSCC](https://arxiv.org/abs/2006.12314)] Always-On, Sub-300-nW, Event-Driven Spiking Neural Network based on Spike-Driven Clock-Generation and Clock- and Power-Gating for an Ultra-Low-Power Intelligent Device. [__`digital`__][__`asic`__]
- [[IEEE-JSSC](https://ieeexplore.ieee.org/document/8998338)] Tianjic: A unified and scalable chip bridging spike-based and continuous neural computation. [__`digital`__][__`asic`__]
- [[IEEE-RAW](https://arxiv.org/abs/2004.06061)] FPGA Based Emulation Environment for Neuromorphic Architectures. [__`digital`__][__`fpga`__][[Code](https://github.com/UA-RCL/RANC)]
- [[IEEE-A-SSCC](https://ieeexplore.ieee.org/document/9336142)] 0.5V 4.8 pJ/SOP 0.93μW Leakage/core Neuromorphic Processor with Asynchronous NoC and Reconfigurable LIF Neuron. [__`digital`__][__`asic`__]
- [[IEEE-ISSCC](https://ieeexplore.ieee.org/document/9062979)] A 74 TMACS/W CMOS-RRAM Neurosynaptic Core with Dynamically Reconfigurable Dataflow and In-situ Transposable Weights for Probabilistic Graphical Models. [__`mixed-signal`__]
- [[Springer-JCST](https://jcst.ict.ac.cn/fileup/1000-9000/PDF/2020-2-21-9686.pdf)] SIES: A Novel Implementation of Spiking Convolutional Neural Network Inference Engine on Field-Programmable Gate Array [__`digital`__][__`fpga`__]
- [[IEEE/ACM-ISCA](https://users.cs.utah.edu/~rajeev/pubs/isca20s.pdf)] SpinalFlow: An Architecture and Dataflow Tailored for Spiking Neural Networks [__`digital`__][__`asic`__]
- [[IEEE/ACM-ICCAD](https://dl.acm.org/doi/10.1145/3400302.3415608)] Encoding, model, and architecture: systematic optimization for spiking neural network in FPGAs [__`digital`__][__`fpga`__]


### 2019

- [[IEEE-TBioCAS](https://arxiv.org/abs/1804.07858)] A 0.086-mm2 12.7-pJ/SOP 64k-Synapse 256-Neuron Online-Learning Digital Spiking Neuromorphic Processor in 28nm CMOS. [__`digital`__][__`asic`__][__`open-source`__][[ODIN](https://github.com/ChFrenkel/ODIN)][[TinyODIN](https://github.com/ChFrenkel/tinyODIN)]
- [[IEEE-TBioCAS](https://arxiv.org/abs/1904.08513)] MorphIC: A 65-nm 738k-Synapse/mm2 Quad-Core Binary-Weight Digital Neuromorphic Processor With Stochastic Spike-Driven Online Learning. [__`digital`__][__`asic`__]
- [[IJSSC](https://ieeexplore.ieee.org/document/8588363)] A 4096-Neuron 1M-Synapse 3.8-pJ/SOP Spiking Neural Network With On-Chip STDP Learning and Sparse Weights in 10-nm FinFET CMOS. [__`digital`__][__`asic`__]
- [[IEEE-CICC](https://web.eecs.umich.edu/~zhengya/papers/cho_cicc19.pdf)] A 2048-Neuron Spiking Neural Network Accelerator With Neuro-Inspired Pruning And Asynchronous Network On Chip In 40nm CMOS. [__`digital`__][__`asic`__]
- [[IEEE-JSSC](https://ieeexplore.ieee.org/document/8867974)] A 65-nm Neuromorphic Image Classification Processor With Energy-Efficient Training Through Direct Spike-Only Feedback. [__`digital`__][__`asic`__]
- [[IEEE-ISVLSI](https://picture.iczhiku.com/resource/ieee/SHKwGhQOijggRvXX.pdf)] RRAM-based Spiking Nonvolatile Computing-In-Memory Processing Engine with Precision-Configurable In Situ Nonlinear Activation. [__`mixed-signal`__]

### 2018

- [[IEEE-MICRO](https://redwood.berkeley.edu/wp-content/uploads/2021/08/Davies2018.pdf)] Loihi: A Neuromorphic Manycore Processor with On-Chip Learning. [__`digital`__][__`asic`__]
- [[IEEE-TBioCAS](https://ieeexplore.ieee.org/document/8094868)] A Scalable Multicore Architecture With Heterogeneous Memory Structures for Dynamic Neuromorphic Asynchronous Processors (DYNAPs). [__`mixed-signal`__]
- [[IEEE-JPROC](https://ieeexplore.ieee.org/document/8591981)] Braindrop: A Mixed-Signal Neuromorphic Architecture With a Dynamical Systems-Based Programming Model. [__`mixed-signal`__][[Thesis](https://stacks.stanford.edu/file/druid:sg377qc5355/thesis_toplevel-augmented.pdf)]

### 2017 

- [[IEEE-ISVLSI](https://ieeexplore.ieee.org/document/8008536)] A 3.43TOPS/W 48.9pJ/pixel 50.1nJ/classification 512 analog neuron sparse coding neural network with on-chip learning and classification in 40nm CMOS. [__`mixed-signal`__]

### 2015

- [[IEEE-TCAD](https://redwood.berkeley.edu/wp-content/uploads/2021/08/Akopyan2015.pdf)] TrueNorth: Design and Tool Flow of a 65 mW 1 Million Neuron Programmable Neurosynaptic Chip. [__`digital`__][__`asic`__]
- [[Frontiers](https://www.frontiersin.org/articles/10.3389/fnins.2015.00141/full)] A reconfigurable on-line learning spiking neuromorphic processor comprising 256 neurons and 128K synapses. [__`mixed-signal`__]
- [[IEEE-ISVLSI](http://vlsisp.engin.umich.edu/wp-content/uploads/sites/334/2017/11/kim-vlsi-2015.pdf)] A 640M pixel/s 3.65mW sparse event-driven neuromorphic object recognition processor with on-chip learning.
- [[IEEE-TBioCAS](https://arxiv.org/pdf/1412.3233)] A Biological-Realtime Neuromorphic System in 28 nm CMOS Using Low-Leakage Switched Capacitor Circuits.

### 2014 

- [[IEEE-BioCAS](https://ieeexplore.ieee.org/document/6981816)] A 65k-neuron 73-Mevents/s 22-pJ/event asynchronous micro-pipelined integrate-and-fire array transceiver.
- [[IEEE-JPROC](https://ieeexplore.ieee.org/document/6805187)] Neurogrid: A Mixed-Analog-Digital Multichip System for Large-Scale Neural Simulations. [__`mixed-signal`__]
- [[IEEE-TVLSI](https://ieeexplore.ieee.org/document/6701396)] Minitaur, an Event-Driven FPGA-Based Spiking Network Accelerator. [__`digital`__][__`fpga`__]

### 2013

- [[IEEE-MICRO](https://ieeexplore.ieee.org/document/6515159)] SpiNNaker: A 1-W 18-Core System-onChip for Massively-Parallel Neural Network Simulation. [__`digital`__][__`asic`__]

### 2011

- [[IEEE-CICC](https://ieeexplore.ieee.org/document/6055293)] A 45nm CMOS neuromorphic chip with a scalable architecture for learning in networks of spiking neurons.

### 2010

- [[IEEE-ISCAS](https://ieeexplore.ieee.org/document/5536970)] A wafer-scale neuromorphic hardware system for large-scale neural modeling. [__`mixed-signal`__]
