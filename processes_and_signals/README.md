# Processes and Signals

This directory contains Bash scripts for managing processes and signals in Linux.

## Scripts

- **0-what-is-my-pid**: Displays the PID of the current script
- **1-list_your_processes**: Displays all running processes for all users with hierarchy
- **2-show_your_bash_pid**: Displays lines containing the word bash using ps
- **3-show_your_bash_pid_made_easy**: Displays PID and name of bash processes using pgrep
- **4-to_infinity_and_beyond**: Displays "To infinity and beyond" indefinitely with 2s sleep
- **5-dont_stop_me_now**: Stops the 4-to_infinity_and_beyond process using kill
- **6-stop_me_if_you_can**: Stops 4-to_infinity_and_beyond without using kill or killall
- **7-highlander**: Displays "To infinity and beyond" and handles SIGTERM with "I am invincible!!!"
- **67-stop_me_if_you_can**: Stops the 7-highlander process
- **8-beheaded_process**: Kills the 7-highlander process with SIGKILL
- **10-process_and_pid_file**: Creates PID file and handles multiple signals
- **11-manage_my_process**: Init script to start, stop, and restart manage_my_process
- **manage_my_process**: Daemon that writes "I am alive!" to /tmp/my_process every 2 seconds
