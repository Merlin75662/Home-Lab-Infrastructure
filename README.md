# 🏠 Enterprise-Grade Home Laboratory
**Infrastructure & Virtualization Showcase**

This repository documents the architecture and services of my personal home laboratory, which serves as a testing ground for network administration, cybersecurity, and local AI deployment.

## 🖥️ Hardware Specifications
* **Servers:** * Dell PowerEdge R630
  * Dell PowerEdge R640
* **Compute/AI:** NVIDIA Tesla P4 GPU for accelerated AI workloads.
* **Storage:** Enterprise-grade SAS/SATA storage arrays in RAID configurations.

## ⚙️ Virtualization & Services
* **Hypervisor:** Proxmox VE Cluster managing highly available virtual machines and LXC containers.
* **Networking & DNS:** * VLAN segmentation for traffic isolation.
  * Pi-hole for network-wide DNS sinkholing.
  * Nginx Proxy Manager for secure SSL termination and reverse proxying.
* **AI & LLMs:** Self-hosted models managed via Ollama and Open WebUI.

## 🛡️ Security Implementation
* Implementation of internal network security policies and firewall rules.
* Regular vulnerability scanning and service monitoring.
