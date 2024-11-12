# What to monitor:

1:Total, used, and free memory
2: Swap usage
3: Buffers and cache

# Commands and tools:
## free: 
Summarizes memory usage.

ex: free -h

## vmstat:
Provides memory and swap information.
## top/htop:
Shows real-time memory usage per process.
## ps aux --sort=-%mem:
Lists processes by memory usage.

# Key indicators:
Low free memory or high swap usage can indicate memory pressure.
High cache usage can be normal but should be understood in context.
