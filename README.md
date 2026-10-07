# Shell Scripts

A collection of practical Bash scripts built during my #90DaysOfDevOps journey, focused on Linux automation, system checks, server maintenance, and log analysis.

## 📂 Repository Structure

| Directory | Focus |
|---|---|
| `basics/` | Bash fundamentals, input, conditions, and service checks |
| `loops-and-arguments/` | Loops, arguments, package automation, and error handling |
| `functions-and-system/` | Functions, strict mode, scope, and system information |
| `server-maintenance/` | Backups, log rotation, and maintenance automation |
| `log-analysis/` | Error detection, log analysis, reporting, and archiving |

## 🔧 Scripts

### Basics

- `hello.sh` — Basic Bash script
- `variables.sh` — Variables and quoting
- `greet-input.sh` — Interactive user input
- `check_number.sh` — Conditional number checking
- `file_check.sh` — File existence validation
- `server_check.sh` — Linux service status check

### Loops & Arguments

- `for_loop.sh` — Iterates through a list
- `count.sh` — Numeric `for` loop
- `countdown.sh` — `while` loop countdown
- `greet.sh` — Command-line argument handling
- `args_demo.sh` — Bash positional arguments
- `install_packages.sh` — Package installation automation
- `safe_script.sh` — Basic error handling

### Functions & System

- `functions.sh` — Reusable Bash functions
- `disk_checks.sh` — Disk and memory checks
- `stricts_demo.sh` — `set -euo pipefail`
- `local_demo.sh` — Function variable scope
- `systems_info.sh` — System information reporting

### Server Maintenance

- `backup.sh` — Timestamped compressed backups
- `log_rotation.sh` — Compress and remove old logs
- `maintenance.sh` — Combines routine maintenance tasks

### Log Analysis

- `sample_logs_generator.sh` — Generates test log data
- `critical.sh` — Detects critical log events
- `error_count.sh` — Counts log errors
- `input_validate.sh` — Validates log input
- `summary_log.sh` — Generates log summaries
- `top_error.sh` — Identifies frequent errors

## Engineering Focus

**Automate repetitive work → validate inputs → handle failures → inspect systems → produce useful output**

## 📚 Related Work

Part of my [90 Days of DevOps](https://github.com/Ashish-6-24/90DaysOfDevOps) learning journey.

## ▶️ Run a Script

```bash
chmod +x script.sh
./script.sh
