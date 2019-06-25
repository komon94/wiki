<!-- TITLE: File System Utilization -->
<!-- SUBTITLE: A quick summary of File System Utilization -->

# Header
1. **Find large files**
find . -xdev -size +1000000c -type f -exec ls -l {} ; | sort -k5n | tail -20