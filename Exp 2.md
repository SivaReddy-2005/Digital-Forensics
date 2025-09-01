# Experment - 2:- Recovery of Deleted or Damaged Files from Storage Device Using TestDisk

## Aim
To recover deleted or damaged files from a storage device using TestDisk, a powerful open-source data recovery software.

## Description
TestDisk is an open-source utility designed to recover lost partitions and make non-booting disks bootable again. It can also recover deleted files from FAT, NTFS, exFAT, and ext2 filesystems. The tool works by scanning the storage device for lost partitions or files and allows users to restore them without altering the original data. It is widely used in forensic investigations and data recovery scenarios where data loss has occurred due to accidental deletion, corruption, or partition damage.

## Tools and Equipment Used
- **TestDisk Software**: Open-source data recovery tool.

- **Storage Device**: The device from which files are deleted or damaged.

- **Forensic Workstation or Computer**: System with TestDisk installed and having access to the storage device.

- **Write Blocker (optional but recommended)**: To prevent any writes to the storage device during recovery to ensure data integrity.






## Procedure
1. **Prepare the Environment**: Install TestDisk on the forensic workstation or computer. Connect the storage device via a write blocker if available.
![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 230941.png>)
2. **Launch TestDisk**: Open TestDisk from the command line or graphical interface depending on the operating system.
![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 231005.png>)
3. **Select Storage Device**: Choose the correct storage device from the list to analyze.
![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 231019.png>)
4. **Select Partition Table Type**: TestDisk usually detects the partition table type automatically (e.g., Intel/PC, EFI GPT).
![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 231030.png>)
5. **Analyze the Disk**: Choose “Analyze” to scan the partitions on the device.
![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 231043.png>)
6. **Search for Lost Partitions**: Perform a deeper search if lost or damaged partitions are not initially found.
![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 231106.png>)
7. **List Files**: Once lost partitions are found, select the partition and choose to list files.
8. **Recover Deleted Files**:
   - Navigate through the directory structure.
   - Mark files or folders for recovery by selecting them.
   - Copy the selected files to a different storage location (never recover to the original device).
   ![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 231159.png>)
9. **Additional Recovery**: If files are damaged, TestDisk tries to recover intact files. For severely damaged files, additional tools might be necessary.
![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 231214.png>)
10. **Exit TestDisk**: After recovery, safely exit the program.
![alt text](<Screen Shorts/Exp 2/Screenshot 2025-09-01 231230.png>)
## Result
Deleted or damaged files from the storage device are recovered successfully and saved to a separate location without altering the original media. The recovery process maintains the integrity of the original data, allowing further forensic examination or file restoration.

