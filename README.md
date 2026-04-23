# 🏠 Enterprise Home Laboratory
**Infrastructure, Virtualization & AI Showcase**

This repository documents the architecture and services of my personal home laboratory, which serves as a testing ground for network administration, cybersecurity, and local AI deployment.

## 🖥️ Hardware Specifications
* **Primary Compute Node:** Dell PowerEdge **R630**.
* **Accelerator:** **NVIDIA Tesla P4** GPU, utilized for hardware-accelerated LLM workloads via PCIe passthrough.
* **Fabrication:** **Ender 3** and **Ender 3 S1** running **Klipper** firmware for custom server cooling and mounting solutions.

## ⚙️ Virtualization & Orchestration
* **Hypervisor:** **Proxmox VE** managing various virtual machines and LXC containers.
* **Network Services:**
    * **DNS & Ad-blocking:** Pi-hole implementation for network-wide sinkholing and internal DNS resolution.
    * **Reverse Proxy:** Nginx Proxy Manager (NPM) for secure SSL termination and internal traffic routing.
* **Local AI Stack:** **Ollama** and **Open WebUI** providing a private, secure interface for LLM interaction.

## 🛡️ Network Architecture & Security
* **VLAN Segmentation:** Logical isolation of management, IoT, and production service networks to maintain a Zero Trust environment.
* **Service Hosting:** Management of private **AzerothCore** and **Palworld** servers, focusing on backend database integrity and network accessibility.
* **Monitoring:** Proactive health monitoring of server temperatures and service uptime.
