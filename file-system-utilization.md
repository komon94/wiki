<!-- TITLE: File System Utilization -->
<!-- SUBTITLE: Cheatbook for File System Utilization -->

# File System Utilization

**2. 1. Find large files**
find . -xdev -size +1000000c -type f -exec ls -l {} \; | sort -k5n | tail -20