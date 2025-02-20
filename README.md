# Inception-of-Things (IoT)

## Description

The **Inception-of-Things (IoT)** project is a system administration exercise designed to deepen your understanding of Kubernetes, containerization, and orchestration using tools like **K3s**, **K3d**, **Vagrant**, and **Argo CD**. The project is divided into three mandatory parts and an optional bonus part, each focusing on different aspects of setting up and managing a Kubernetes cluster.

---

## Objectives

- Set up a Kubernetes cluster using **K3s** and **Vagrant**.
- Deploy and manage multiple applications in a Kubernetes environment.
- Use **K3d** to simplify Kubernetes cluster management.
- Implement continuous integration and deployment using **Argo CD**.
- (Optional) Integrate **Gitlab** into the Kubernetes cluster for advanced CI/CD workflows.

---

## Requirements

- **Vagrant**: For creating and managing virtual machines.
- **K3s**: Lightweight Kubernetes distribution.
- **K3d**: Tool to run K3s in Docker containers.
- **Docker**: For containerization.

---

## Project Structure

The project is divided into three mandatory parts and one optional bonus part. Each part has specific tasks and deliverables.

### Mandatory Parts

1. **Part 1: K3s and Vagrant**
   - Set up two virtual machines using Vagrant.
   - Install K3s in controller mode on the first machine and in agent mode on the second.
   - Configure SSH access and networking between the machines.

2. **Part 2: K3s and Three Simple Applications**
   - Deploy three web applications in a K3s cluster.
   - Configure Ingress to route traffic based on the hostname.
   - Ensure that one of the applications has multiple replicas for scalability.
  
  ![image](https://github.com/user-attachments/assets/beb970dc-b013-4ef6-8a48-993ed103dfe9)

3. **Part 3: K3d and Argo CD**
   - Set up a Kubernetes cluster using K3d.
   - Implement continuous integration and deployment using Argo CD.
   - Deploy an application from a public GitHub repository and manage its versions.


  ![image](https://github.com/user-attachments/assets/9b6257d4-f65e-4de7-8582-a0c80db16917)

### Bonus Part

- Integrate **Self hosted Gitlab** into the Kubernetes cluster.
- Ensure that all functionalities from Part 3 work with the local Gitlab instance.

---
