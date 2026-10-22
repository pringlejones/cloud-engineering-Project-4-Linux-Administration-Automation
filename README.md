# cloud-engineering-Project-4-Linux-Administration-Automation
# Project 4: Linux Systems Administration & Automated Maintenance Architecture

## 📌 Project Overview
Engineered an automated shell scripting framework designed to manage core Linux system architectures. Implemented strict user/group access configurations (`chmod`/`chown`), built defensive data protection storage boundaries, and constructed a reusable maintenance suite that automates historical log clearing, storage status checks, and compressed configuration archives.

## 🏗️ Core Admin Executions & Scripts
* **Role Isolation Access Controls:** Configured dedicated group topologies (`sysadmins`) and test account contexts (`engineer01`). Locked down system subfolders (`/opt/secure_data`) utilizing exact octal permission masks (`770`) to isolate infrastructure access paths.
* **Automated System Cleanup (`maintenance.sh`):** Formulated a specialized script that automatically sweeps `/var/log` paths to locate and truncate outdated history structures older than 14 days, protecting system drives from running out of disk space.
* **Storage Metrics Diagnostics:** Programmed custom string parsing arrays using `awk` utilities to log storage capacity allocations straight to dedicated tracking repositories.
* **Backup Compression Pipelines:** Built automated `tar` extraction workflows to create compressed copies of the primary `/etc` system configuration directory, saving them securely inside a `/backup` location labeled by date stamps.

## 📁 Repository Artifacts
* `README.md` - Operational guide and script specifications.
* `maintenance.sh` - Bash automation script for log sweeps & backups.

## 📸 Automation Script Execution Verification

### Script Execution & Status Log Verification:
<img width="1003" height="708" alt="Screenshot (13) - Copy" src="https://github.com/user-attachments/assets/328ba259-967e-43c0-ac49-709da31b603f" />

