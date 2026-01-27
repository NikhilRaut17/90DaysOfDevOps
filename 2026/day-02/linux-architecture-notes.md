Day 2 -> Task:

1.Core component of Linux?
 
•	Kernel:   The kernel is the core of Linux.
•	 It manages hardware resources like CPU, memory, disk, and devices.
•	  It handles system calls, process scheduling, and memory management
•	Shell: A command-line interpreter that acts as an interface between the user and the kernel, such as Bash.
•	User Space Applications: Applications like GUIs, browsers, or editors that interact with the system through the shell or libraries. 
Init / systemd
•	init or systemd is the first process started by the kernel (PID 1).
•	It is responsible for starting and managing system services.
•	Modern Linux uses systemd instead of traditional init.

2. How Processes Are Created and Managed
•	A process is a running program in Linux.
•	New processes are created using fork() system call.
•	The kernel assigns each process a unique Process ID (PID).
•	The kernel schedules processes using CPU time sharing.
•	Processes can be:
o	Running
o	Sleeping
o	Stopped
o	Zombie
Commands used to manage processes:
•	ps → view processes
•	top / htop → monitor processes
•	kill → stop a process
3. What systemd Does and Why It Matters
•	systemd is the service manager in modern Linux systems.
•	It:
o	Starts services during boot
o	Restarts failed services
o	Manages logs using journald
o	Controls background services (daemons)
Why it matters:
•	Faster boot time
•	Better service management
•	Automatic recovery of failed services
•	Essential for running servers and cloud systems reliably

