<!-- TITLE: File System Utilization -->
<!-- SUBTITLE: Cheatbook for File System Utilization -->

# File System Utilization

**Find large files**
find . -xdev -size +1000000c -type f -exec ls -l {} \; | sort -k5n | tail -20