# 0x05-processes_and_signals

This directory contains Bash scripts that demonstrate various concepts related to process management and signals in Linux. Each script addresses a specific task, ranging from identifying process IDs to sending signals for termination and signal handling.

## Table of Contents

* [0. What Is My PID?](#0-what-is-my-pid)
* [1. List Your Processes](#1-list-your-processes)
* [2. Show Your Bash PID](#2-show-your-bash-pid)
* [3. Show Your Bash PID Made Easy](#3-show-your-bash-pid-made-easy)
* [4. To Infinity and Beyond](#4-to-infinity-and-beyond)
* [5. Don't Stop Me Now!](#5-dont-stop-me-now)
* [6. Stop Me if You Can](#6-stop-me-if-you-can)
* [7. Highlander](#7-highlander)
* [8. Beheaded Process](#8-beheaded-process)

## General Requirements

All scripts in this directory adhere to the following conventions:

* The first line of each Bash script starts with `#!/usr/bin/env bash`.
* The second line of each Bash script is a comment explaining what the script does.
* An optional blank line may be included for neatness after the comment.
* The core logic of the script is typically concise and follows after the comment/blank line.
* All files are executable (`chmod u+x filename`).

---

### 0. What Is My PID?

This script displays its own Process ID (PID).

**File:** `0-what-is-my-pid`

```bash
#!/usr/bin/env bash
# This script displays its own Process ID (PID).

echo $$
