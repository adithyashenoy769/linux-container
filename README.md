# Linux Container from Scratch

A lightweight Linux container implementation built from scratch using **namespaces**, **cgroups**, and **seccomp**. This project demonstrates how containerization works at a low level by isolating processes, managing resources, and enforcing security policies.

---

## Features
- **Process Isolation**: Uses Linux namespaces to isolate processes, filesystems, and network stacks.
- **Resource Management**: Leverages cgroups to control CPU, memory, and I/O usage for containerized processes.
- **Security**: Applies seccomp filters and drops unnecessary Linux capabilities to reduce the attack surface.
- **User-Friendly CLI**: Provides a simple command-line interface for creating and managing containers.

---

## How It Works
1. **Namespaces**: Isolates processes using namespaces for PID, mount, network, and user.
2. **Cgroups**: Manages resource allocation (CPU, memory, I/O) using control groups.
3. **Seccomp**: Filters system calls to enforce security policies and prevent unauthorized actions.
4. **CLI**: Allows users to create and manage containers with commands like `./container -u <uid> -m <dir> -c <command>`.

---
