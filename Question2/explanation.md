Command: mkdir ~/documents
Explanation: Creates a directory named "documents" inside the home directory.

Command: cd ~/documents
Explanation: Changes the current working directory to the "documents" directory.

Command: touch plan.txt
Explanation: Creates an empty file named "plan.txt".

Command: echo "Project reminder: Complete setup tasks" > plan.txt
Explanation: Writes sample project-related text into the file "plan.txt".

Command: ls -l plan.txt
Explanation: Displays file permissions, ownership, size, and confirms the user owns the file.

Command: cp plan.txt plan_copy.txt
Explanation: Creates a duplicate of "plan.txt" named "plan_copy.txt".

Command: mv ~/documents ~/project_documents
Explanation: Renames the directory from "documents" to "project_documents".

Command: mkdir ~/project_documents/archive
Explanation: Creates a subdirectory named "archive" inside "project_documents".

Command: mv ~/project_documents/plan_copy.txt ~/project_documents/archive/
Explanation: Moves the copied file into the archive directory.

Command: ls -R ~/project_documents
Explanation: Lists all files and subdirectories inside "project_documents" recursively.

Command: realpath ~/project_documents/archive/plan_copy.txt
Explanation: Displays the absolute path of the moved file.

