# Simx-Simulator


*   Getting Started

Simulator
=========

Prerequisites
-------------

1.  Ensure you have the latest NVIDIA drivers for your [CUDA-enabled](https://developer.nvidia.com/cuda-gpus) graphics card.
    
    ![](./Getting Started_files/nvidia_driver2.png) ![](./Getting Started_files/nvidia_driver1.png)
    
    Even if not prompted by the system, a restart is recommended to ensure the new drivers are correctly detected prior to running any simulations.
    
    In case the driver cannot be updated using the above method, please visit [NVIDIA Download Page](https://www.nvidia.com/Download/index.aspx) to download the latest driver.
    

Windows Simulator
-----------------

1.  Extract the archive to a common location like `C:/SimxAI`.
2.  If downloading for the first time, you will need to download the license.txt file , unless one has been provided directly from simx.ai. Copy the attached lic.txt file to the extracted location `C:/SimxAI/lic.txt`.
3.  Run the simulator by launching `C:/SimxAI/Simx.exe`.

Linux Simulator
---------------

1.  Extract the archive to a common location like `~/SimxAI`.
2.  If downloading for the first time, you will need to download the license.txt file , unless one has been provided directly from simx. Copy the attached license.txt file to the extracted location `~/SimxAI/lic.txt`.
3.  Run the simulator by navigating the `~/SimxAI/Simx` directory and running the shell script `Simx.sh`.

Open Source Clients
-------------------

Working with the SimX Simulator can be done directly through TCP/IP communications with any application that conforms to the Simx API. However, SimX provides several reference implementations of clients in C++, LabVIEW, and Python. The SimX Clients are open source and available to all users of the SimX Simulator.

