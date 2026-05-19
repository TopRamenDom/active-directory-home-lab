# Troubleshooting Notes

## Issue 1 - Installed Server Core Instead of Desktop Experience

Problem:
Installed Windows Server Core accidentally and only received a command-line interface.

Resolution:
Reinstalled Windows Server 2022 using:
- Windows Server 2022 Standard Evaluation (Desktop Experience)

---

## Issue 2 - NAT Network Name Missing

Problem:
VirtualBox NAT Network dropdown showed no available network names.

Resolution:
Created a NAT Network manually through:
File → Tools → Network Manager

Assigned both VMs to:
- NatNetwork

---

## Issue 3 - No Bootable Device Found

Problem:
Virtual machine failed to boot because no ISO was mounted.

Resolution:
Mounted the Windows Server ISO manually through VirtualBox storage settings.
