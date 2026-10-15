
# Linux System Report Generator

A lightweight Bash utility designed to collect fundamental system metrics on a Linux machine and export them into a structured text document.

## Metrics Collected
- Hostname
- Kernel Version
- Disk Usage (`df -h`)
- Memory Usage (`free -m`)
- Top Running Processes sorted by CPU consumption (`ps`)

## Usage Instructions

1. *Clone the repository:*
   git clone <REPO_URL>
   cd <REPO_DIRECTORY>
2. *execution permissions:*
  chmod +x system_report.sh
3. *bash script execution:*
  ./system_report.sh
4. *view generated report:*
   cat system-report.txt
