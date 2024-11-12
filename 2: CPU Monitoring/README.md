# What to monitor:
CPU load and usage percentages
CPU load averages over time
Temperature and core usage
# Commands and tools:
## top:
Provides a real-time view of processes and CPU usage.

## htop:
Enhanced version of top (if installed).
## mpstat: 
Monitors CPU usage per core.

ex: mpstat -P ALL 1
## vmstat: 
Shows system processes, memory, swap, I/O, and CPU.

## vmstat 1

# Key indicators:
High load averages relative to CPU core count
High %idle indicates low CPU usage, low %idle indicates high usage
