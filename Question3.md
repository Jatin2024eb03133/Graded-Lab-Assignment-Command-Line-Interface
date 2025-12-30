You have been asked to understand how Linux manages files using links and disk usage information.As part of your role, you will perform the following operations within your own user space.

1. File Creation
Create a file named sample_data.txt in your home directory and add some sample text to it.
Answer: 
```bash
touch sample_data.txt
echo "Sample content" > sample_data.txt

2. Hard Link Creation
Create a hard link to sample_data.txt named sample_hard.txt.
Answer:
ln sample_data.txt sample_hard.txt

3. Symbolic Link Creation
Create a symbolic (soft) link to sample_data.txt named sample_soft.txt.
Answer: ln -s sample_data.txt sample_soft.txt

4. Inode Verification
Display the inode numbers of sample_data.txt, sample_hard.txt, and sample_soft.txt.
Answer: ls -i sample_data.txt sample_hard.txt sample_soft.txt


5. Inode Analysis
Identify which files share the same inode number and briefly explain the reason.
Answer: Hard link shares same inode as original file.


6. File Metadata Inspection
Display detailed file information (permissions, ownership, size, timestamps) of sample_data.txt.
Answer: ls -l sample_data.txt

7. Disk Usage Check
Display the disk usage of your home directory in a human-readable format.
Answer: du -h ~

8. File Size Overview
Display the size of each file present in your home directory in a human-readable format.
Answer: ls -lh

9. Link Deletion Test
Delete the symbolic link sample_soft.txt and verify that the original file sample_data.txt is unaffected.
Answer: rm sample_soft.txt

10. Disk Utility Demonstration
Demonstrate the usage of du and df commands using various useful options and briefly explain the output.
Answer:
du -h
df -h
