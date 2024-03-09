
![oschaos_dark_logo](./statics/oschaos-dark-logo-without-bg.png)

![oschaos_light_logo](./statics/oschaos-light-logo-without-bg.png)

## Intro on app

| Specification | Value |
|---|---|
| Application name | oschaos |
| Type of application | Console |
| Installation mode | Binary/Potable |
| Type of targets | Remote/On-premise |


## Functionality

**oschaos** is a dedicated command line tool for generating chaos experiment in operating system. It can be either used inside the server itself where user wants to generate chaos, or it can also perform chaos by doing SSH into the server either with normal credentails or keyring file (*.prem) file.

## Experiments oschaos can do for you

### Windows  
- **CPU Hog**: Simulate high CPU usage to test system performance under heavy load.
- **Memory Hog**: Allocate excessive memory to assess how the system handles memory exhaustion.
- **Disk Space Fill:** Fill up disk space to evaluate the system's behavior when storage runs low.
- **Service Stoppage:** Stop critical services to observe the impact on system availability.
- **Network Partition:** Simulate network outages or disruptions to test network resilience.
- **Process Termination:** Abruptly terminate key processes to see how the system recovers.
- **File Corruption:** Introduce corrupted files to evaluate data integrity and recovery mechanisms.
- **System Reboot:** Force a system reboot to test startup processes and recovery mechanisms.


### Linux
- **CPU Burn:** Stress test the CPU by maxing out its usage.
- **Memory Exhaustion:** Allocate large amounts of memory to assess the system's handling of memory constraints.
- **Disk I/O Stress:** Generate heavy disk I/O to evaluate disk performance and resilience.
- **Network Partitioning:** Simulate network partitions to test distributed system behavior.
- **Process Killing:** Terminate critical processes to observe the system's response and recovery.
- **Kernel Panic Injection:** Intentionally trigger kernel panics to test system stability and recovery procedures.
- **File System Corruption:** Introduce file system corruption to assess data recovery mechanisms.
- **Power Failure Simulation:** Simulate sudden power loss to evaluate system integrity and recovery upon reboot.
