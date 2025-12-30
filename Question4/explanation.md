Command: uptime
Explanation: Displays how long the system has been running since the last boot along with load averages.

Command: ps -u $USER
Explanation: Lists all processes currently running under the logged-in user account.

Command: ps -u $USER -o pid,comm,%cpu --sort=-%cpu | head -n 2
Explanation: Shows the user process consuming the highest CPU by sorting processes based on CPU usage.

Command: sleep 300 &
Explanation: Starts a command in the background that runs for 300 seconds.

Command: jobs
Explanation: Displays background jobs running in the current shell session.

Command: renice 5 -p <PID>
Explanation: Changes the priority (niceness) of a running process to a lower priority.

Command: ps -o pid,ni,comm -p <PID>
Explanation: Verifies the updated priority value of the selected process.

Command: free -h
Explanation: Displays memory usage including total, used, and free memory in human-readable format.

Command: df -h ~
Explanation: Shows disk space usage of the filesystem where the home directory is located.

Command: echo $SHELL
Explanation: Displays the name of the shell currently in use.

Command: uname -a > system_report.txt
Explanation: Redirects system information output into a file named system_report.txt.

Command: ncdu ~
Explanation: Opens an interactive disk usage analyzer showing space consumed by files and directories in the home directory.