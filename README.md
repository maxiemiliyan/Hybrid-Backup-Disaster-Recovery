
# Hybrid Backup and Disaster Recovery using Azure Backup and Azure Site Recovery

This project demonstrates how to implement a **Hybrid Backup and Disaster Recovery (DR)** solution using Microsoft Azure services. It includes:

- **Azure Backup**: To back up critical files and folders from an on-premises VM to the cloud using the Microsoft Azure Recovery Services (MARS) agent.


- **Azure Site Recovery (ASR)**: To replicate an entire Hyper-V virtual machine to Azure for disaster recovery.

---

## Project Objectives

- Set up file/folder-level backup from an on-prem VM to Azure.
- Replicate a Hyper-V virtual machine to Azure using ASR.
- Test recovery by performing a test failover in Azure.
- Document each step with screenshots for clarity.

---

## Environment Setup

| Component              | Details                                      |
|------------------------|----------------------------------------------|
| Host Machine           | Windows 11 with Hyper-V enabled              |
| Guest VM               | Windows Server 2019                          |
| Azure Services Used    | Recovery Services Vault, Azure Backup, ASR   |
| Tools Installed        | MARS Agent, ASR Provider                     |

---

## Outcomes

- Successfully backed up files from a local VM to Azure.
- Replicated a Hyper-V VM to Azure for DR.
- Performed a successful test failover to verify DR readiness.

---


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


