Command: echo "This is sample data for link testing" > ~/sample_data.txt
Explanation: Creates a file named sample_data.txt in the home directory and writes sample text into it.

Command: ln ~/sample_data.txt ~/sample_hard.txt
Explanation: Creates a hard link named sample_hard.txt that points to the same inode as sample_data.txt.

Command: ln -s ~/sample_data.txt ~/sample_soft.txt
Explanation: Creates a symbolic (soft) link that references sample_data.txt using its file path.

Command: ls -i ~/sample_data.txt ~/sample_hard.txt ~/sample_soft.txt
Explanation: Displays inode numbers of the original file, hard link, and symbolic link to compare them.

Command: ls -l ~/sample_data.txt
Explanation: Displays detailed file metadata including permissions, ownership, size, and timestamps.

Command: du -sh ~
Explanation: Shows the total disk usage of the home directory in a human-readable format.

Command: ls -lh ~
Explanation: Lists all files in the home directory along with their sizes in a human-readable format.

Command: rm ~/sample_soft.txt
Explanation: Deletes the symbolic link while leaving the original file unaffected.

Command: ls ~/sample_data.txt
Explanation: Confirms that the original file still exists after deleting the symbolic link.

Command: du -ah ~ | head
Explanation: Displays disk usage of files and directories recursively in a readable format.

Command: df -h
Explanation: Shows overall filesystem disk space usage including total, used, and available space.