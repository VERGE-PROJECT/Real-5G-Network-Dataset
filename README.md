# Real-5G-Network-Dataset
Overview
This dataset contains real-time performance metrics from 5G live network, including KPIs like signal strength, bandwidth, latency, and node reliability. It supports the training of AI/ML models for optimizing and monitoring network operations. Researchers can use it to model behavior, predict disruptions, and enhance both efficiency and user experience, driving innovation in 5G network management.

![image](https://github.com/user-attachments/assets/bb10a1fa-caf9-48e5-9a2d-538e2bacfedd)


Note: Although the actual dataset cannot be shared on GitHub due to sensitivity concerns, the information of this file is provided to help others understand what type of data exists, support alignment with common standards, and enable future collaboration.

# Dataset Contents/Dataset Description
The dataset includes a variety of measurement files that cover different aspects of 5G network performance. These files contain data on:

•	PDCP (Packet Data Convergence Protocol) measurements

•	Cell user quantity measurements- number of users per cell

•	Throughput and data volume

•	PRB (Physical Resource Block) measurements

•	Channel quality measurements

•	Dual connectivity (DC) performance measurements

•	Cell algorithm measurements

•	gNB (next-generation Node B) algorithm measurements

•	QCI (QoS Class Identifier) throughput measurements

•	RRC (Radio Resource Control) reestablishment measurements

•	DRB (Data Radio Bearer) measurements

•	RRC setup measurements

•	UE (User Equipment) context release measurements

The dataset configuration file is included to help users better understand the dataset and to provide details about the network setup. This file contains information such as frequency bands, uplink and downlink bandwidth, cell radius, subcarrier spacing, cyclic prefix length, slot structure, and SSB subcarrier spacing for each cell associated with a gNB.

For each measurement, the associated counter units (e.g., bits, count, seconds, dBm) along with a brief description are provided to ensure clarity and consistency in interpretation.

# Dataset format

The dataset is provided in .csv format, so no special software or prerequisites are required to access or use it.

There is a small glimpse of provided dataset that contains throughput and data volume for each gNB that is configured under each cell.

![image](https://github.com/user-attachments/assets/8578c782-3eb7-483b-907a-6a51f08d4137)

# Citation

Please cite our paper if this information can help you.

1.	Cite the dataset itself.

2.	@article{Real5GNetw,
    author = {S. Kosu, G. Kalem},

  	title = {Enabling Innovation through VERGE's Open Data Space based on 5G Network},

    year = {Jan. 2024},

    journal = {Wireless World Research Forum Meeting 50 (WWRF #50)}

}
# Contact

Gökham Kalem (gokhan.kalem@turkcell.com.tr)
