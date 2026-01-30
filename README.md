
# DevOps Journey 🚀

## Day 1 – Linux Basics (WSL)

### Commands Learned
- pwd – show current directory
- ls – list files
- cd – change directory
- mkdir – create directory
- touch – create file
- rm -r – delete files/folders
- cat – view file content
- nano – edit files

### File Permissions
- rwx permissions
- chmod – change permissions
- chown – change ownership

### Notes
- rm -r deletes directories recursively
- chmod 755 is common for scripts
- sudo gives admin access

✅ Day 1 completed successfully


## Day 2 – Linux File Handling, Logs & Git (WSL)

### Commands Learned

- cp – copy files and directories
- mv – move or rename files
- tree – view directory structure
- find – search files recursively
- locate – fast file search using database
- head – view first lines of a file
- tail – view last lines of a file
- grep – search text inside files
- whoami – show current user
- id – display user and group information
- ls -l – view file permissions
- chmod – change file permissions
- chown – change file ownership
- git status – check repository state
- git add – stage changes
- git commit – save changes
- git push – upload changes to GitHub
- Log Handling
- Created log files for practice
- Used grep to search ERROR and WARN messages
- Used tail -f for live log monitoring

### Permissions Practice

- Understood rwx permissions for user, group, others
- Practiced numeric permissions (644, 755, 777)
- Tested permission denied scenarios
- GitHub Notes
- Updated README with learning summary
- Committed changes with meaningful messages
- Pushed updates to remote repository


✅ Day 2 completed successfully

## Day 3 – Process, Disk & Memory Management

### Commands Learned

- Process & System Monitoring
- ps aux – list all running processes
- top – real-time system monitoring
- htop – interactive process viewer
- kill – terminate a process gracefully
- kill -9 – force kill unresponsive process
- uptime – check system running time and load average
- Disk & Memory Management
- df -h – check disk usage in human-readable format
- du -sh – check size of directories/files
- free -m – check memory usage in MB
- Practical Tasks
- Ran background processes using sleep &
- Identified process ID (PID) using ps aux
- Killed running processes using kill and kill -9
- Checked disk utilization using df -h
- Identified top disk-consuming directories using du
- Monitored system memory using free -m

### Notes
- High CPU or stuck processes can slow down servers
- Disk full issues are one of the main causes of production outages
- Always monitor disk usage before deployments
- Check available memory, not just free memory

  ✅ Day 3 completed successfully


## Day 4 – Log Management (Core DevOps Skill)

### Commands Learned

- tail -f – monitor log file in real time
- less – view large log files efficiently
- grep -i – search text ignoring case
- | (pipe) – pass output of one command to another

### Practical Tasks

- Created a sample log file (app.log)
- Viewed logs using less
- Searched ERROR messages using grep -i error
- Searched WARN messages using grep -i warn
- Monitored logs live using tail -f

### Notes

- Logs are the first place to check when applications fail
- tail -f is commonly used during live incident debugging
- Using pipe (|) improves troubleshooting speed
- Most DevOps work revolves around logs and monitoring

### GitHub Update

- Updated README with Day 3 and Day 4 learning notes
- Committed and pushed changes to GitHub
- Maintaining daily DevOps learning consistency

### Git Commands Used
- git add README.md
- git commit -m "Day 3 & Day 4: Process, Disk, Memory & Log Management"
- git push origin main

✅ Day 4 completed successfully
