# What to monitor:
1:System logs for errors or warnings

2:Security logs for unauthorized access attempts

# Commands and tools:
## tail:
Views recent entries in logs.

ex: tail -f /var/log/syslog
## journalctl: 
Views system logs (especially for systemd services).
ex: journalctl -u <service-name>

## grep: 
Filters logs by keywords or specific events.

ex:grep "error" /var/log/syslog

# Key indicators:
Frequent errors or warnings could indicate misconfigurations.

Unauthorized access attempts in security logs need attention.


![text](https://github.com/Mohamedsaaidi/Linux-System-Monitoring/blob/main/Images/Screenshot%202024-11-13%20at%2011.12.07.png)

