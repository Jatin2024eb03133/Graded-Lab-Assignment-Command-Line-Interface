1. User Identity Verification

Display your currently logged-in username and all groups your user account belongs to.
**Command:
'''bash
whoami
groups

Your name or login ID must appear in the output.
Answer:
student 
student sudo**

2. Workspace Validation

Display the current working directory and list all files and directories in that location using long format listing.
**Answer:
pwd 
ls -l**

3. Environment Confirmation File

Create a file named user_info.txt and write the line:
&quot;Linux user environment verified&quot;

**Answer:
excho "Linux user environment verified" > user.info.txt**



4. File Integrity Check

Display the number of characters present in user_info.txt.
Answer:
**bash
wc -c user.info.txt**

5. Learning the Tools

Access the manual page of the mkdir command. Identify one useful option and briefly explain what it does.
**bash
man mkdir**  **Explanation: (-p creates parent directories if they do not exist.)**

6. Home Directory Inspection

List the contents of your home directory sorted alphabetically.
**Answer: 
ls ~**


7. Log Investigation

Search for the word &quot;admin&quot; inside a file named log.txt and display only the matching lines.
**Answer:
grep "admin" log.txt**

8. System Information Check

Display the Linux kernel version currently running.
**Answer: grep "admin" log.txt**

9. Network Connectivity Test

Verify network connectivity by sending ICMP packets to www.google.com.
**Answer:** 
**ping -c 4 www.google.com**

10. System Health Awareness

Display the command used to check system uptime and briefly explain its output (uptime duration, number of users, load average).
**Answer: uptime**
