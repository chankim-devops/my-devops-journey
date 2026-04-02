[2026-04-01] Linux System Administration & Resource Monitoring

1. Network & DNS Troubleshooting
DNS resolution via nameserver configuration.

Internal diagnostic via Loopback interface (127.0.0.1).

Commands:

Bash
ip addr                # Check network interfaces (lo, eth0)
cat /etc/resolv.conf   # Verify DNS nameserver settings
ping -c 3 127.0.0.1    # Test internal network stack
2. Process & Resource Control
Real-time CPU/Memory monitoring and analysis.

Understanding available memory vs free memory.

Signal management for unresponsive processes (SIGKILL).

Commands:

Bash
top                    # Monitoring real-time processes
free -h                # Check memory status (Human-readable)
sudo kill -9 [PID]     # Forceful termination of a process
history | tail -n 20   # Review recently executed commands
3. File Permissions & Security
Permission bit calculation (r=4, w=2, x=1).

Implementing Least Privilege for file access.

Commands:

Bash
ls -l [filename]       # View detailed file permissions
chmod 600 [filename]   # Restrict to Owner: Read/Write only
umask                  # Check default permission mask
4. System Logs (Next Session)
Path: /var/log/

---
