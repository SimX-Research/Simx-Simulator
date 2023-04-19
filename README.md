# Simx-Simulator

The Simx Simulator provides users with the ability to test AV and AMR algorithms in one of several pre-made Simx Simulator levels. The Open Source Simx clients provide an API and examples for connecting to the Simulator for simulating traffic scenarios and replaying Simx trajectory files. The clients allow users to configure and test any number of configurations of Simx high-fidelity sensors.

![image](https://user-images.githubusercontent.com/131154677/233154122-c1f98b0d-5313-492b-be7e-8ecb076e0f72.png)



*   Getting Started

Prerequisites
-------------

1.  Ensure you have the latest NVIDIA drivers for your [CUDA-enabled](https://developer.nvidia.com/cuda-gpus) graphics card.
    
    Even if not prompted by the system, a restart is recommended to ensure the new drivers are correctly detected prior to running any simulations.
    
    In case the driver cannot be updated using the above method, please visit [NVIDIA Download Page](https://www.nvidia.com/Download/index.aspx) to download the latest driver.
    

Windows Simulator
-----------------
1.  Clone this repo for LabVIEW API
2.  Download the Simulator https://drive.google.com/drive/folders/1p8bt2IKcjN6ag92KVQXSFHTU-kftmD0Z?usp=share_link
3.  Extract the archive to a common location like `C:/SimxAI`.
4.  If downloading for the first time, you will need to download the lic.txt file , you can request lic.txt by contact info@simx.ai . 
5.  Copy the attached lic.txt file to the extracted location `C:/SimxAI/lic.txt`.
6.  Run the simulator by launching `C:/SimxAI/Simx.exe`.
7.  Run LabVIEW Example `Autonomous Mobile Robots.vi`

Linux Simulator
---------------

1.  Extract the archive to a common location like `~/SimxAI`.
2.  If downloading for the first time, you will need to download the license.txt file , unless one has been provided directly from simx. Copy the attached license.txt file to the extracted location `~/SimxAI/lic.txt`.
3.  Run the simulator by navigating the `~/SimxAI/Simx` directory and running the shell script `Simx.sh`.

Open Source Clients
-------------------

Working with the SimX Simulator can be done directly through TCP/IP communications with any application that conforms to the Simx API. However, SimX provides several reference implementations of clients in C++, LabVIEW, and Python. The SimX Clients are open source and available to all users of the SimX Simulator.

