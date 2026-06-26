SCREENSHOTS - TASK 01
═══════════════════════════════════════════════════════════════════

This folder contains screenshots of Nmap terminal output from the scans performed for Task 01.

═══════════════════════════════════════════════════════════════════
SCREENSHOT DESCRIPTIONS
═══════════════════════════════════════════════════════════════════

1. basic_scan.png
   - Command: nmap [target_ip]
   - Shows: Basic scan results with open ports (21, 22, 80, 3306)

2. service_version.png
   - Command: nmap -sV [target_ip]
   - Shows: Service version detection (vsftpd 3.0.5, OpenSSH 10.2p1, 
             Apache 2.4.66, MariaDB 11.8.6)

3. os_detection.png
   - Command: sudo nmap -O [target_ip]
   - Shows: OS fingerprinting result (Linux Kernel 5.0 - 6.2)

4. full_scan.png
   - Command: sudo nmap -sV -O -A [target_ip] -oN full_scan.txt
   - Shows: Comprehensive aggressive scan output

═══════════════════════════════════════════════════════════════════
ALTERNATIVE DOCUMENTATION
═══════════════════════════════════════════════════════════════════

All scan outputs are fully documented in:
- Task01.docx (Full report with embedded screenshots)
- nmap_scan_results.txt (Structured results)
- scan_commands.txt (All commands used)

These screenshots serve as visual evidence of the scanning process.

═══════════════════════════════════════════════════════════════════
NOTE
═══════════════════════════════════════════════════════════════════

If actual screenshot images are not available, all terminal outputs
are reproduced textually in the report and result files.

═══════════════════════════════════════════════════════════════════
END
═══════════════════════════════════════════════════════════════════