# Linux Server Hardening & Security Labs

Practices, scripts, and documentation for securing Linux production environments.

---

## Lab 01: SSH Server Hardening (`/etc/ssh/sshd_config`)

### Objective
Secure remote access on Ubuntu/Debian Linux servers by disabling root login, enforcing SSH key-based authentication, and changing default access rules.

### Key Modifications
1. **Disable Password Authentication** (Enforce SSH Keys):
   ```bash
   PasswordAuthentication no
   PubkeyAuthentication yes
