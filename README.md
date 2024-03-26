# NEGSC
A self-supervised graph representing learning method named NEGSC, is proposed to identify the types of network intrusion attacks for edge-sensitive net flow traffic.

• The graph self-attention mechanism for edge-oriented features, named NEGAT, is introduced, to obtain graph representation encoding from the raw netflow data while avoids a great increase in computational complexity for attention weights between edges.

• NEGSC focuses on edge features, can automatically extract feature representations in local graph structures, and generate positive and negative samples for training without manual labels, and has good adaptability and flexibility for real-time detection of network traffic.

• We introduced this unsupervised method into the multi-classification task of network intrusion detection for the first time, and achieved the results with potential application in both the multi-classification and binary classification tasks.

# Preliminaries

## Installation

•[Pytorch](https://pytorch.org/)
•[DGL](https://www.dgl.ai/)

## NIDS dataset

Four kinds of NetFlow datasets were selected, including **NF-BoT-IoT**, **NF-CSE-CIC-IDS2018**, **NF-BoT-IoT-v2**, and **NF-CSE-CIC-IDS2018- v2**. All these datasets support binary and multi-class classification predictions.

*URL*:  
[https://staff.itee.uq.edu.au/marius/NIDS_datasets/](https://staff.itee.uq.edu.au/marius/NIDS_datasets/).

*References*:  
[1] Sarhan M, Layeghy S, Moustafa N, et al. Netflow datasets for machine learning-based network intrusion detection systems[C]. Big Data Technologies and Applications: 10th EAI International Conference, BDTA 2020, and 13th EAI International Conference on Wireless Internet, WiCON 2020, Virtual Event, December 11, 2020, Proceedings 10. Springer International Publishing. 2021: 117-135.

[2] Sarhan M, Layeghy S, Portmann M. Towards a standard feature set for network intrusion detection system datasets[J]. Mobile networks and applications. 2022: 1-14.

# Environments

• *Python version: 3.10.8 (main, Nov 4 2022, 13:48:29) [GCC 11.2.0]*;  
• *PyTorch version: 1.13.1*;  
• *GPU: NVIDIA GeForce RTX 4090, 24GB of GPU memory*;  
• *CPU: Inteli9-13900k*;  
• *OS: Linux Ubuntu 22.04 Jammy Jellyfish*.  

• *jupyter-notebook version: 6.5.3*;  
• *Jupyter version: 1.0.0*;  
• *Jupyter_client version: 8.0.3*;  
• *Jupyter-console version: 6.6.3*;  
• *Jupyter_core version: 5.2.0*;  
• *Jupyter-events version: 0.6.3*;  
• *Jupyter_server version: 2.4.0*;  
• *Jupyter_server_terminals version: 0.4.4*;  
• *Jupyterlab-pygments version: 0.2.2*;  
• *Jupyterlab-widgets version: 3.0.5*.  

# Info

• ***Any issues regarding the paper is welcome, please contact us for help***.

**Authors’ information**:

•*Address: Central South University of Forestry and Technology, 498 Shaoshan South Road, Tianxin District, Changsha, Hunan Province. China*;

•*Name&Email: Renjie Xu email: 446364661@qq.com*.

•The doi of our paper will be upload later..

Thanks for reading！

----Edited by Renjie Xu  
March 2024
