You are working as a junior system administrator responsible for organizing project- related files in your home directory.

Your supervisor wants you to demonstrate your understanding of Linux file and directory management commands.

1. Project Workspace Setup

Create a directory named documents inside your home directory. This directory will store your project-related files.
Answer:
```markdown
```bash
mkdir ~/documents

2. File Creation

Navigate into the documents directory and create a file named plan.txt.
**Answer:
cd ~/documents
touch plan.txt**

3. Content Addition

Write some sample text of your choice into the plan.txt file. The content can be a short project note or reminder.
**Answer: echo "Project plan created" > plan.txt**

4. File Metadata Verification

Display the permissions and ownership details of the plan.txt file. Ensure your username appears in the output.
**Answer: ls -l plan.txt**

5. File Duplication

Create a copy of plan.txt and name it plan_copy.txt.
**Answer: cp plan.txt plan_copy.txt**

6. Directory Renaming

Rename the documents directory to project_documents to reflect the project scope more clearly.
**Answer: mv documents project_documents**


7. Archival Structure

Inside the project_documents directory, create a subdirectory named archive.
**Answer: mkdir project_documents/archive**

8. File Organization

Move plan_copy.txt into the archive subdirectory.
**Answer: mv plan_copy.txt project_documents/archive/**

9. Recursive Listing

List all files and subdirectories inside project_documents recursively so that the complete directory structure is visible.
**Answer: ls -R project_documents**

10. Path Verification

Display the absolute path of the plan_copy.txt file after it has been moved to the archive directory.
**Answer:
realpath project_documents/archive/plan_copy.txt**

yaml
Copy code


