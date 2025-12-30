Question 4 [5 points]

You must perform all operations without making any configuration changes to the system.

These tasks should be executed within your own user account. Since uptime, processes, memory usage,disk usage, and background jobs vary across systems and users, each student’s output will be unique.
1. System Uptime Verification
Display the time elapsed since the system was last booted.
**Answer:
```bash
uptime**

2. User Process Listing
List all processes currently running under your user account.
**Answer:
ps -u $USER**

3. CPU Usage Analysis
Identify the process that is consuming the highest CPU usage among your running processes.
**Answer:
top**

4. Background Process Execution
Start a command in the background and verify that it is running.
**Answer:
sleep 100 &**

5. Process Priority Management
Change the priority (niceness) of one of your running processes and display the updated priority.
**Answer:
renice 10 -p <PID>**

6. Memory Usage Monitoring
Display memory usage information in a human-readable format.
**Answer:
free -h**

7. Disk Space Inspection
Display the disk space usage of the filesystem where your home directory resides.
**Answer:
df -h**

8. Shell Identification
Display the name of the shell currently in use.
**Answer:
echo $SHELL**

9. Output Redirection
Redirect the output of a system information command of your choice into a file named system_report.txt.
**Answer:
uname -a > system_report.txt**


10. Disk Usage Visualization
Demonstrate the usage of the ncdu tool using appropriate options and briefly explain what it shows.
**Answer:
ncdu**
