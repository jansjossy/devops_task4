# devops_task4
# DevOps Internship - Task 4: Shell Scripting

**Student:** Janzj
**Environment:** Ubuntu 24.04 (WSL)

## 1. System Monitor Script (`monitor.sh`)
**Objective:** Automate system health checks (Uptime and Disk Usage).
**Features Used:**
- **Variables:** Used `$DATE` and `$DISK_USAGE` to store dynamic system data.
- **Conditionals:** Implemented an `if-else` block to trigger a warning if disk usage exceeds 80%.
- **Command Chaining:** Used `df`, `grep`, and `awk` to extract precise disk percentages.

## 2. Backup Automation Script (`backup_script.sh`)
**Objective:** Automate the backup of log files to a specific directory.
**Features Used:**
- **Loops:** Used a `for` loop to iterate through all `.txt` files in the directory.
- **File Operations:** Checked file existence with `[ -f ]` and used `cp` to create `.bak` copies.
- **Directory Management:** Used `mkdir -p` to ensure the backup destination exists.

## 3. Execution Evidence
*Attached below are screenshots demonstrating:*
1. Successful execution of `./monitor.sh` showing system stats.
2. Successful execution of `./backup_script.sh` showing file backup loop.
3. Correct file permissions (`rwx`) set using `chmod +x`.

<img width="960" height="1020" alt="Screenshot 2026-01-20 110111" src="https://github.com/user-attachments/assets/c76878e2-43d5-47f2-a03a-4258d290ce87" />
<img width="960" height="1020" alt="Screenshot 2026-01-20 110049" src="https://github.com/user-attachments/assets/71563b6d-41ed-440a-a476-d3765def17a5" />
<img width="960" height="1020" alt="Screenshot 2026-01-20 110124" src="https://github.com/user-attachments/assets/b1bb34bb-8b53-4db0-ac8b-2533ff64e2c9" />
<img width="960" height="1020" alt="Screenshot 2026-01-20 110121" src="https://github.com/user-attachments/assets/a559f112-715e-4bf7-893a-61924cfcb181" />
