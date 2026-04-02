# Linux System Administration & Resource Monitoring

##  2026-04-01

Today I organized the core topics of Linux system administration and resource monitoring.  
Focused on the most practical areas: network/DNS troubleshooting, process & memory control, file permissions, and system logs.

---

### Network & DNS Troubleshooting

DNS resolution through nameserver configuration and internal diagnostics using the Loopback interface (127.0.0.1).

**Commands:**

```bash
ip addr                  # Check network interfaces (lo, eth0)
cat /etc/resolv.conf     # Verify DNS nameserver settings
ping -c 3 127.0.0.1      # Test internal network stack

2. Process & Resource Control
Real-time CPU/Memory monitoring, understanding available vs free memory, and signal management for unresponsive processes (SIGKILL).
Commands:
Bashtop                      # Real-time process monitoring
free -h                  # Check memory status (human-readable)
sudo kill -9 [PID]       # Forceful termination of a process (SIGKILL)
history | tail -n 20     # Review recently executed commands

3. File Permissions & Security
Permission bit calculation (r=4, w=2, x=1) and applying the Least Privilege principle.
Commands:
Bashls -l [filename]         # View detailed file permissions
chmod 600 [filename]     # Restrict to owner: Read/Write only
umask                    # Check default permission mask
