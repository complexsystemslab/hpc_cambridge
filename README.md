# hpc_cambridge

HPC options Cambridge


https://docs.hpc.cam.ac.uk/hpc/user-guide/policies.html#service-level-3-free-usage


https://docs.hpc.cam.ac.uk/hpc/

university-wide CSD3 computing cluster (https://docs.hpc.cam.ac.uk/hpc/), which has 90 nodes each with 4x A100 80GB GPUs

Sign up here

https://www.hpc.cam.ac.uk/rcs-application

students can get 3000 GPU hours per quarter for free https://docs.hpc.cam.ac.uk/hpc/user-guide/policies.html#service-level-3-free-usage

There is a queueing/job submission system using SLURM 


https://www.cst.cam.ac.uk/local/sys/resources/gpu

 

We provide shared servers to allow researchers and ACS / Part III students to quickly get started developing and testing code that needs GPUs (and/or a lot of CPU resource).  The shared GPU development servers have a single GPU and are intended for testing and development work when you will only intermittently need access to a GPU, running your experimental code for up to a few minutes at most, to keep the impact on other users to a minimum.  Once your code is working and needs to be run for more than a few minutes at a time, you should move to another system (preferably the High Performance Computing Service); see below.

PhD students, researchers and faculty can use the shared server dev-gpu-1.cl.cam.ac.uk which has a single A100 GPU (or the CPU development server, dev-cpu-1.cl.cam.ac.uk, when you don't need a GPU).

ACS (MPhil / Part III) students can use the shared server dev-gpu-acs.cl.cam.ac.uk which has a single P100 GPU (or the CPU development server, dev-cpu-acs.cl.cam.ac.uk, when you don't need a GPU).

Unfortunately this service is not available for Part II projects.

If you have not used SSH to connect to a departmental server before, see our SSH documentation.  You cannot log in using just a password; you will probably need to set up a VPN and Kerberos.

 https://www.hpc.cam.ac.uk/rcs-application


I know that the department also has some resources available internally, but I know very little about what is available here, somewhere to start:

https://www.cst.cam.ac.uk/local/sys/resources/gpu

https://wiki.cam.ac.uk/cl-sys-admin/How_to_use_GPUs


