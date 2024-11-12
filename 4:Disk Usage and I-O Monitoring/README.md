# What to monitor:
1: Disk space usage per partition
2: Disk I/O and latency
3: File system errors
# Commands and tools:
## df -h:
Displays disk space usage.

## du: 
Checks directory and file sizes.
ex:  du -sh /path/to/directory

## iostat: 
Monitors disk I/O statistics.
ex: iostat -xz 1

## lsblk:
Shows available and mounted block devices.

# Key indicators:
High disk usage (80% or more) may require attention.
High disk I/O or latency can indicate bottlenecks in storage.
