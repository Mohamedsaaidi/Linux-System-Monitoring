

# Tools and scripts:
## cron: 
Schedule regular monitoring scripts.

ex: crontab -e
## sar:
Part of sysstat, records system performance data.
ex: sar -u 1 5

## logrotate:
Manages and archives logs.

### Sample script to log CPU and memory usage:
#!/bin/bash
echo "Logging system metrics" >> /var/log/sys_monitor.log

echo "Date: $(date)" >> /var/log/sys_monitor.log

echo "CPU Usage:" >> /var/log/sys_monitor.log

top -bn1 | grep "Cpu(s)" >> /var/log/sys_monitor.log

echo "Memory Usage:" >> /var/log/sys_monitor.log

free -h >> /var/log/sys_monitor.log

echo "---" >> /var/log/sys_monitor.log

### Running the script:
Save this script as sys_monitor.sh, make it executable, and set it to run periodically using cron.
