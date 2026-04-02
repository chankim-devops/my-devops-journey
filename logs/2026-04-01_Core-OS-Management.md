# [2026-04-01] Linux System Administration & Resource Monitoring

Today, I focused on the foundational aspects of Linux system management, specifically focusing on how the OS communicates with itself and manages its resources.

## 1. Network & DNS Troubleshooting
- **Key File**: `/etc/resolv.conf`
  - Configured DNS nameservers to resolve domain names to IP addresses.
- **Loopback Interface (`lo`)**:
  - Understanding `127.0.0.1`: Why the system needs to communicate with itself for internal routing and service diagnostics.
- **Command**: `ip addr`
  - Used to identify network interfaces and verify assigned IP addresses.

## 2. Process & Resource Management
- **Monitoring Tools**: Used `top` and `htop` to track real-time CPU and Memory consumption.
- **Memory Analysis**:
  - Analyzed the difference between `free` (completely empty) and `available` (actual memory ready for new tasks).
  - Used `free -h` for human-readable output.
- **Process Control**:
  - Mastered `kill -9 [PID]` to forcefully terminate unresponsive processes via **SIGKILL**.
  - Practiced background job management using `&`, `jobs`, and `fg`.

## 3. File Permissions & Security
- **Permission Structure**: Analyzed symbolic notation (e.g., `-rw-rw-r--`).
- **Octal Calculation**:
  - Practiced mapping `r=4, w=2, x=1` (e.g., `664` = Owner: rw, Group: rw, Others: r).
- **Security Hardening**:
  - Implemented `chmod 600` to restrict sensitive file access to the owner only.
  - Explored `umask` to understand default permission inheritance for new files.

---
