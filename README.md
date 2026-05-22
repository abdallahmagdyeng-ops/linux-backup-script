🔒 Automated Backup Script — IBM Linux Final Project
A shell script that automatically backs up files modified in the last 24 hours, built as the final project for the IBM Linux Commands and Shell Scripting course on Coursera.

📋 Project Overview
Scenario: As a Linux developer at ABC International Inc., I was tasked with automating the backup process for encrypted password files. The script runs daily and backs up any files updated in the past 24 hours — eliminating human error and improving security.

⚙️ How It Works

Takes two arguments: source directory and destination directory
Gets the current timestamp
Loops through all files in the source directory
Checks if each file was modified in the last 24 hours
Compresses all modified files into a .tar.gz archive
Moves the archive to the destination directory
Runs automatically every 24 hours via cron job


🚀 Usage
bashchmod +x backup.sh
./backup.sh /path/to/source /path/to/destination

🕐 Cron Job
bash0 0 * * * /usr/local/bin/backup.sh /path/to/source /path/to/destination

📚 Course
IBM Linux Commands and Shell Scripting — Coursera — IBM

👤 Author
Abdallah — May 2026
