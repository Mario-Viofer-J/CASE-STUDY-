# CASE-STUDY-
### NAME: MARIO VIOFER J
### REG NO: 212223100032
Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

Case Study Questions – OpenStack Calculation in Cloud Computing

1. Resource Utilization:

Based on the current infrastructure, what is the total available compute capacity in terms of:
Total vCPUs
Total RAM
Total storage

2.Storage Allocation:

Given 10 TB of total block storage across the cloud, how many VMs can be supported if:
a) Each VM is allocated 100 GB block storage
b) Snapshot storage consumes 20% extra on average

## SOLUTIONS:
### Problem 1: Encryption Time Calculation
#### Given:
1 MB takes 0.05 seconds to encrypt.
Total data = 2 TB = 2048 GB = 2,097,152 MB
#### Solution:
Time = 2,097,152 MB × 0.05 seconds = 104,857.6 seconds
#### Answer:
104,857.6 seconds or approximately 29.13 hours

### Problem 2: CPU Utilization Efficiency
#### Given:
Allocated vCPUs = 8
Used vCPUs (average) = 5.5
#### Solution:
Efficiency = (5.5 / 8) × 100 = 68.75%
#### Answer:
68.75% CPU utilization efficiency

### Problem 3: Network Throughput Efficiency
#### Given:
Max bandwidth = 1 Gbps
Peak usage = 600 Mbps
#### Solution:
Convert 1 Gbps to Mbps: 1 Gbps = 1000 Mbps
Efficiency = (600 / 1000) × 100 = 60%
#### Answer:
60% network throughput efficiency

### Problem 4: Energy Efficiency
#### Given:
Setup A: 500W for 2 hours = 500 × 2 = 1000 Wh
Setup B: 300W for 3.5 hours = 300 × 3.5 = 1050 Wh
#### Solution:
Since both processed the same workload, lower energy usage = more efficient
#### Answer:
Setup A is more energy-efficient

### Problem 5: Maximum VMs for Efficient Hosting
#### Given:
Physical cores = 16
Each VM uses = 2 cores
Optimal utilization = 75% of 16 = 12 cores
#### Solution:
Max number of VMs = 12 / 2 = 6 VMs
#### Answer:
6 VMs can be efficiently hosted
