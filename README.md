# NEGSC
A self-supervised graph representing learning method named NEGSC, is proposed to identify the types of network intrusion attacks for edge-sensitive net flow traffic.

• The graph self-attention mechanism for edge-oriented features, named NEGAT, is introduced, to obtain graph representation encoding from the raw netflow data while avoids a great increase in computational complexity for attention weights between edges.

• NEGSC focuses on edge features, can automatically extract feature representations in local graph structures, and generate positive and negative samples for training without manual labels, and has good adaptability and flexibility for real-time detection of network traffic.

• We introduced this unsupervised method into the multi-classification task of network intrusion detection for the first time, and achieved the results with potential application in both the multi-classification and binary classification tasks.

# Preliminaries

## Framework

•[Pytorch](https://pytorch.org/)<br />
•[DGL](https://www.dgl.ai/)

## NIDS dataset

Four kinds of NetFlow datasets were selected, including **NF-BoT-IoT**, **NF-CSE-CIC-IDS2018**, **NF-BoT-IoT-v2**, and **NF-CSE-CIC-IDS2018- v2**.
All these datasets support binary and multi-class classification predictions.

*URL*:<br />
https://staff.itee.uq.edu.au/marius/NIDS_datasets/.

*References*:<br />
[1] Sarhan M, Layeghy S, Moustafa N, et al. Netflow datasets for machine learning-based network intrusion detection systems[C]. 
Big Data Technologies and Applications: 10th EAI International Conference, BDTA 2020, and 13th EAI International Conference on Wireless Internet, WiCON 2020,
Virtual Event, December 11, 2020, Proceedings 10. Springer International Publishing. 2021: 117-135.

[2] Sarhan M, Layeghy S, Portmann M. Towards a standard feature set for
network intrusion detection system datasets[J]. Mobile networks and applications. 2022: 1-14.

# Run
We have uploaded Pre-trained Models and sample data, which can be directly tested by running test.ipynb.

# Environments

• *Python version*: 3.10.8 (main, Nov  4 2022, 13:48:29) [GCC 11.2.0];<br />
• *PyTorch version*: 1.13.1;<br />
• *GPU*: NVIDIA GeForce RTX 4090, 24GB of GPU memory;<br />
• *CPU*: Inteli9-13900k;<br />
• *OS*: Linux Ubuntu 22.04 Jammy Jellyfish.<br />

• *jupyter-notebook version*: 6.5.3;<br />
• *Jupyter version*: 1.0.0;<br />
• *Jupyter_client version*: 8.0.3;<br />
• *Jupyter-console version*: 6.6.3;<br />
• *Jupyter_core version*: 5.2.0;<br />
• *Jupyter-events version*: 0.6.3;<br />
• *Jupyter_server version*: 2.4.0;<br />
• *Jupyter_server_terminals version*: 0.4.4;<br />
• *Jupyterlab-pygments version*: 0.2.2;<br />
• *Jupyterlab-widgets version*: 3.0.5.<br /> 

# Info

• ***Any issues regarding the paper is welcome, please contact us for help***.<br />

**Authors’ information**:<br />

•*Address: Central South University of Forestry and Technology, 498 Shaoshan South Road, Tianxin District, Changsha, Hunan Province. China*;

•*Name&Email: Renjie Xu email: renjiexu@csuft.edu.cn*. <br />

•The doi of our paper will be upload later..

Thanks for reading！

----Edited by Renjie Xu<br />
March 2024
