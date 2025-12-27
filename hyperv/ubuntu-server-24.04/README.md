# Ubuntu Server 24.04 LTS on Hyper-V

## Purpose
Establish a secure, reproducible Ubuntu Server baseline running on Hyper-V,
suitable for further infrastructure experimentation and automation.

## Host Environment
- Host OS: Windows 11 Pro
- Hypervisor: Hyper-V (Client)
- Hardware: Ryzen 9 5900X, 64 GB RAM

## Virtual Machine Configuration
- Generation: 2 (UEFI)
- Memory: 16 GB
- Storage: 80 GB VHDX
- Networking: Hyper-V Default Switch (NAT)

## Operating System
- Ubuntu Server 24.04.3 LTS
- Standard installation (not minimized)
- LVM enabled
- Ubuntu Pro not enabled

## Initial Configuration
- Static IPv4 address configured via Netplan
- OpenSSH server installed
- SSH access verified from host system
- Basic admin tools installed

## Security Baseline
- Root login disabled
- SSH access confirmed post-hardening

## Recovery Strategy
- Hyper-V checkpoint created:
  **Baseline – Static IP + SSH working**

## Outcome
A clean Ubuntu Server baseline ready for service deployment,
security hardening, and automation in future lab phases.
