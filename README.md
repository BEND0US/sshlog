# ⚡sshlog
A strace-based tool to monitor SSH login attempts

> ⚠️ For educational and auditing purposes only. This tool is not intended for malicious use.

**SSHLog** is a low-level auditing tool that uses `strace` to monitor the `sshd` daemon and capture authentication-related system call data. While SSH encrypts all credential information, analyzing system call sequences can still reveal useful metadata, such as attempted usernames and indirect password hints during login attempts.
