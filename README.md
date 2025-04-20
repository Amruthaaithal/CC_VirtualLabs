# 🧠 OS Microservices Simulation

## 📌 Overview
This project simulates core operating system functionalities using microservices:
- **Memory Management** – Simulation of allocation and deallocation of memory.
- **Process Scheduling** – Simulation of algorithms like FCFS, Round Robin and SJF
- **Multithreading** – Simulates thread creation, execution, and synchronization.

- **IPC** - simulation of shared memory and pipes
- **System Call** - simulation of various system calls

Each service is containerized using Docker and communicates via REST APIs.

Integration of services:
process_scheduler writes data to shared memory, which in turn can be read by memory_manager

---


To visualise the microservices, download the zip file, navigate to the directory and build the container.

Make sure Docker is installed and running:

docker-compose up --build
