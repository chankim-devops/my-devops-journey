# 2026-04-01 Core OS Management & Resource Monitoring
[TIL] Linux System Administration & Process Management
1) Network & DNS Troubleshooting
Key File: /etc/resolv.conf

Concept: DNS resolution for domain names (e.g., https://www.google.com/search?q=google.com).

Loopback IP: 127.0.0.1 (Self-communication for system diagnostics).

Command: ip addr to check local and interface IP addresses.

2) Process & Resource Monitoring
top / htop: Real-time CPU and Memory usage tracking.

free -h: Memory analysis (Understanding available vs free).

kill -9 [PID]: Forcefully terminating unresponsive processes (SIGKILL).

Background Jobs: Running tasks with & and managing them with jobs and fg.

3) File Permissions & Security
Structure: -rw-rw-r-- (Owner, Group, Others).

Octal Mode: 664 (Calculated as r=4, w=2, x=1).

Command: chmod 600 to restrict access to only the owner.

umask: Default permission mask for newly created files.
