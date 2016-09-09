# vMotion_Migration

VMware VMotion 
VMware VMotion allows the live migration of running virtual machines from one physical server to another with zero downtime, continuous service availability, and complete transaction integrity.
VMotion can be used to
•	Improve hardware utilization.
•	Allow continued virtual machine operation while accommodating scheduled hardware downtime. 
•	Allows vSphere Distributed Resource Scheduler to balance virtual machines across hosts.
![vmotion_migration_process](https://cloud.githubusercontent.com/assets/19299815/18391337/5086d682-76cb-11e6-8e40-149104a39530.jpg)
Requirements to perform vMotion
•	Must have a shared storage, between two hosts.

No need to copy have to copy only the memory status.
•	vMotion network.
•	Production network.
•	Must not have a connection to a virtual device.
•	Virtual machines cannot have a connection to a vSwitch.
•	Must not have CPU affinity configured.
Source and destination hosts must have.
•	Visibility to all storage used by the virtual machine
•	At least a Gigabit Ethernet network
•	Access to the same physical networks
•	Compatible CPUs 
![capture](https://cloud.githubusercontent.com/assets/19299815/18391371/6aa6a75e-76cb-11e6-9f2d-40839bbed543.JPG)
![capture1](https://cloud.githubusercontent.com/assets/19299815/18391372/6aa78b60-76cb-11e6-833d-ef1e1311f009.JPG)
![capture2](https://cloud.githubusercontent.com/assets/19299815/18391376/6ab5de18-76cb-11e6-9049-06cbc031ea1d.JPG)
![capture3](https://cloud.githubusercontent.com/assets/19299815/18391373/6aabaa2e-76cb-11e6-865c-84b07e736266.JPG)
![capture4](https://cloud.githubusercontent.com/assets/19299815/18391374/6aad09c8-76cb-11e6-80b1-a64c132293ca.JPG)
![capture5](https://cloud.githubusercontent.com/assets/19299815/18391375/6ab21e5e-76cb-11e6-95d5-2b3ed9fa859a.JPG)
![capture6](https://cloud.githubusercontent.com/assets/19299815/18391377/6ade244a-76cb-11e6-84e8-172e9038616d.JPG)
![capture7](https://cloud.githubusercontent.com/assets/19299815/18391378/6adf34c0-76cb-11e6-9d59-278ce9fca762.JPG)
![capture8](https://cloud.githubusercontent.com/assets/19299815/18391379/6ae63c20-76cb-11e6-9718-3c8920158988.JPG)
![capture9](https://cloud.githubusercontent.com/assets/19299815/18391380/6aea506c-76cb-11e6-9e0f-a1b0569b7e2b.JPG)
![capture10](https://cloud.githubusercontent.com/assets/19299815/18391382/6af53d60-76cb-11e6-9141-43658f05d3bc.JPG)
![capture11](https://cloud.githubusercontent.com/assets/19299815/18391381/6af010a6-76cb-11e6-94d0-6c7bad846f47.JPG)
![capture12](https://cloud.githubusercontent.com/assets/19299815/18391383/6b1562f2-76cb-11e6-8a08-907f1c8afd66.JPG)
![capture13](https://cloud.githubusercontent.com/assets/19299815/18391384/6b1794be-76cb-11e6-87d0-be25aa23738d.JPG)
![capture14](https://cloud.githubusercontent.com/assets/19299815/18391385/6b1ca53a-76cb-11e6-82cd-bff388af4514.JPG)
![capture15](https://cloud.githubusercontent.com/assets/19299815/18391386/6b247d46-76cb-11e6-8536-2bc95df09fcf.JPG)
![capture16](https://cloud.githubusercontent.com/assets/19299815/18391387/6b269c34-76cb-11e6-9b75-8d2f2101d83b.JPG)
![capture17](https://cloud.githubusercontent.com/assets/19299815/18391388/6b2e6360-76cb-11e6-8e3d-a8afcc608468.JPG)
![capture18](https://cloud.githubusercontent.com/assets/19299815/18391390/6b4c3e12-76cb-11e6-8d5b-6d5f1e9074a0.JPG)
![capture19](https://cloud.githubusercontent.com/assets/19299815/18391391/6b51d444-76cb-11e6-8ed7-6cc30a8861b5.JPG)
![capture20](https://cloud.githubusercontent.com/assets/19299815/18391392/6b590bba-76cb-11e6-803f-6f3a72273785.JPG)





















