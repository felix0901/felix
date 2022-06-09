---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Skills
#### Proficient: Python, Pytorch, JAX, GCP, Cloud TPU, Verilog
#### Experienced: Tensorflow, C/C++, Matlab

## Research Interest and Experience
#### [ML] ML-based automation, RLs, GA-based optimization, Transformer, Efficient attention for long sequence, Pruning, Quantization, Neural architecture search
#### [Accelerator] DNN accelerator, DNN Mapping/Dataflow, Algorithm-HW co-design



##  Projects
#### DNN Accelerator Design Space Exploration (DSE), GaTech, GA
•	Framed HW DSE into an RL problem and developed a REINFORCE-based algorithm
•	The proposed method outperforms 3 widely used optimization methods (SA, GA, BO) and 6 SOTA RLs
•	Main host of a popular open-sourced DNN accelerator cost model, [MAESTRO](http://maestro.ece.gatech.edu/), and a HW DSE framework, [ConfuciuX](https://github.com/maestro-project/confuciux)
#### DNN Dataflow and Schedule Optimization, GaTech, GA
•	The proposed genetic algorithm (GA)-based DNN dataflow mapper outperforms other optimizers by 10x-100x
•	Developed and hosted an open-sourced DNN dataflow mapper ([GAMMA](https://github.com/maestro-project/gamma)) supporting two most popular open-sourced DNN accelerator cost models MAESTRO and Timeloop
•	Developed a scheduler for multi-tenant DNN workload for multi-core accelerator, MAGMA
•	Developed a generalizable Decision-Transformer-based DNN mapper, DNNFuser
#### Efficient Attention and Transformers, GaTech, GA
•	Model pruning and efficient attention techniques for training large BERT model for long sequence tasks
•	Developed new dataflow tackling the quadratic memory bottleneck of attention layers
#### SW/HW Co-design for DNN Accelerator and Machine Learnings, GaTech, GA
•	Developed an optimized neural-evolution platform with algorithm-HW co-design approach and implemented on FPGA board (PYNQ)
•	Developed a GAN-based HW-aware Neural Architecture Search technique
•	Developed three RL-based methods optimizing Network-on-Chip performance




## Work Experiences
### Intern, Google, CA 05/21' - 08/21'
•	Research project on speed quality trade-off of efficient Transformer model
### Intern, Corporation Technology, Siemens, NJ										   05/19’ – 07/19’
•	Developed Pytorch DNN, RNN quantization module, for fast evaluation of any quantized DNN models


## Publications
1. S.-C. Kao, H Kwon, M Pellauer, A Parashar, T Krishna,"A Formalism of DNN Accelerator Flexibility", ACM SIGMETRICS/Performance conference (SIGMETRICS), Jun 2022
2. S.-C. Kao, T Krishna, "MAGMA: An Optimization Framework for Mapping Multiple DNNs on Multiple Accelerator Cores", HPCA, 2022, [paper](https://arxiv.org/abs/2104.13997)
3. S.-C. Kao, M Pellauer, A Parashar, T Krishna, "DiGamma: Domain-aware Genetic Algorithm for Mapping-HW Co-optimization for DNN Accelerators", Design, Automation and Test in Europe Conference (DATE), March 2022, [paper](https://arxiv.org/abs/2201.11220)
4. S.-C. Kao, X. Huang, T Krishna, “DNNFuser: Generative Pre-Trained Transformer as a Generalized Mapper for Layer Fusion in DNN Accelerators ”, arXiv, Jan 2022, [paper](https://arxiv.org/abs/2201.11218)
5. S.-C. Kao, S. Subramanian, G. Agrawal, T Krishna, "FLAT: An Optimized Dataflow for Mitigating Attention Performance Bottlenecks", arXiv, July 2021, [paper](https://arxiv.org/abs/2107.06419)
6. S.-C. Kao, T Krishna, "E3: A HW/SW Co-design Neuroevolution Platform for Autonomous Learning in Edge Device", IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS), 2021, [paper](https://cpb-us-w2.wpmucdn.com/sites.gatech.edu/dist/c/332/files/2021/04/e3-inax_ispass2021.pdf)
7. S.-C. Kao, T Krishna, “GAMMA: Automating the HW Mapping of DNN Models on Accelerators via Genetic Algorithm”, IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2020, [paper](https://cpb-us-w2.wpmucdn.com/sites.gatech.edu/dist/c/332/files/2020/08/gamma_iccad2020.pdf), [code](https://github.com/maestro-project/gamma), [video](https://www.youtube.com/watch?v=gfBFRBbcA10)
8. S.-C. Kao, G Jeong, T Krishna, “ConfuciuX: Autonomous Hardware Resource Assignment for DNN Accelerators using Reinforcement Learning”, IEEE/ACM International Symposium on Microarchitecture (MICRO), 2020, [paper](https://arxiv.org/pdf/2009.02010.pdf), [code](https://github.com/maestro-project/confuciux), [video](https://www.youtube.com/watch?v=qHuO_38CdWQ)
9. S.-C. Kao, A. Ramamurthy, R. Williams, T Krishna, “Conditional Neural Architecture Search”, Resource-Constrained Machine Learning (ReCoML'20), March 2020, [paper](https://arxiv.org/abs/2006.03969)
10. S.-C. Kao, A. Ramamurthy, T Krishna, "Generative Design of Hardware-aware DNNs", arXiv, 2020, [paper](https://arxiv.org/abs/2006.03968)
11. S.-C. Kao, C.-H. Yang, P.-Y. Chen, X. Ma, T. Krishna, “Reinforcement Learning based Interconnection Routing for Adaptive Traffic Optimization”, IEEE/ACM International Symposium on Networks-on-Chip (NOCS), Oct. 2019, [paper](https://arxiv.org/abs/1908.04484), [code](https://github.com/felix0901/interconnect-routing-gym)
12. S.-C. Kao, D.-Y. Lee, A.-Y. Wu, “Bloom Filter And Implementation Method Thereof”, US Patent, 2020, [paper](https://patentscope.wipo.int/search/en/detail.jsf?docId=US277544115)
13. S.-C. Kao, D.-Y. Lee, A.-Y. Wu, “Dynamically Updatable Ternary Segmented Aging Bloom Filter for OpenFlow-Compliant Low-Power Packet Processing”, IEEE/ACM Transaction On Networking, March 2018, [paper](https://ieeexplore.ieee.org/document/8322446)
14. D.-Y. Lee, S.-C. Kao, A.Y. Wu, “Dynamically Updatable Mechanisms for OpenFlow-compliant Low-power Packet Processing”, Book chapter in “Advances in Networks: Security and Communications: Reviews”, 2019, [paper](https://www.amazon.com/Advances-Networks-Security-Communications-Reviews/dp/8409145103)
15. C.-c. Wang, Y.-T. Chen, D.-Y. Lee, S.-C. Kao, A.-Y. Wu, “Profiling and SW/HW Co-design for Efficient SDN/OpenFlow Data Plane Realization”, IEEE International Conference on Electronics Information and Emergency Communication (ICIEC), July 2017, [paper](https://ieeexplore.ieee.org/abstract/document/8076600?casa_token=LmO1pAYgoQAAAAAA:2Kw-Utns6LMoQOgM6EwT1jafpZ28OF8ZvHmr106mFyuMjQINZrWYijo4n_popQZdllC6-B70AXY)
16. E. Qin, G. Jeong, W. Won, S.-C. Kao, H. Kwon, S. Srinivasan, D. Das, G. Moon, S. Rajamanickam, T. Krishna, “Extending Sparse Tensor Accelerators to Support Multiple Compression Formats”, IEEE International Parallel & Distributed Processing Symposium (IPDPS), May 2021, [paper](https://arxiv.org/pdf/2103.10452.pdf)
## Education
### Georgia Institute of Technology, Atlanta GA, Ph.D. in Electrical and Computer Engineering in Dr. Tushar Krishna's group - [Synergy Lab](https://synergy.ece.gatech.edu/), GPA: 3.75/4.0
**Majoring**: Computer Architecture & Software											   Expt: May 2022
**Selected Coursework**: Machine Learning Hardware Accelerator, Advanced Computer Architecture, High Performance Parallel Computing, Advanced Machine Learning, Interconnection Network, Digital Image Processing
### National Taiwan University, Taipei Taiwan, B.S., M.S. in Electronics Engineering, in Dr. An-Yeu Wu's group - [Access Lab](http://access.ee.ntu.edu.tw/), GPA: 3.95/4.0
**Selected Coursework**: Convex Optimization, GPU Programming, Embedded System




