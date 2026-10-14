# Processes and Signals

Bash scripts covering Linux processes, PIDs, and signals.

## Scripts

| File | Description |
|------|-------------|
| `0-what-is-my-pid` | Displays the script's own PID |
| `1-list_your_processes` | Lists all running processes in user-oriented format with hierarchy |
| `2-show_your_bash_pid` | Displays lines containing the word bash (to find bash PID) |
| `3-show_your_bash_pid_made_easy` | Displays PID and name of processes containing bash |
| `4-to_infinity_and_beyond` | Displays 'To infinity and beyond' indefinitely |
| `5-dont_stop_me_now` | Kills the `4-to_infinity_and_beyond` process |
| `6-stop_me_if_you_can` | Kills `4-to_infinity_and_beyond` without using kill or killall |
| `7-highlander` | Loops forever, displaying 'I am invincible!!!' on SIGTERM |
| `67-stop_me_if_you_can` | Kills the `7-highlander` process |
| `8-beheaded_process` | Kills the `7-highlander` process with SIGKILL |
| `10-process_and_pid_file` | Manages a PID file and handles SIGTERM, SIGINT, SIGQUIT |
| `11-manage_my_process` | Init script to start/stop/restart manage_my_process |
| `manage_my_process` | Daemon that writes 'I am alive!' to /tmp/my_process |
