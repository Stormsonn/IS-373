Application level software-anything you can type into or see
Kernel-Applications send information to te kernel. The kernel connects to the software
Hardware-WSL is simulation the hardware (CPU/Memory/Devices)

Containerization System (Docker)-Provide applications a fake kernel
  The application software can't tell the difference between a real and fake kernel
  The containerization system is creating a "super kernel" as long as one machine is running all the applications will keep running

Single threaded software
  Vertical Scaling-Increasing clock speed or memory
  Horizontal Scaling-Running things in parraell

Most virtual machines per square foot is the most efficient

Orchestration software-orchestrates where the containers run within the data center and what is running on them

The Twelve Factors
I. Codebase
One codebase tracked in revision control, many deploys
II. Dependencies
Explicitly declare and isolate dependencies
III. Config
Store config in the environment
IV. Backing services
Treat backing services as attached resources
V. Build, release, run
Strictly separate build and run stages
VI. Processes
Execute the app as one or more stateless processes
VII. Port binding
Export services via port binding
VIII. Concurrency
Scale out via the process model
IX. Disposability
Maximize robustness with fast startup and graceful shutdown
X. Dev/prod parity
Keep development, staging, and production as similar as possible
XI. Logs
Treat logs as event streams
XII. Admin processes
Run admin/management tasks as one-off processes


History of Virtualization
Where containerization comes from
Difference between Docker and Kubernetes
Layers of the computer(Application Kernel Hardware)
