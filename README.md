# Linux Backup Script

This is my final project for the IBM Linux Commands and Shell Scripting course on Coursera.

## What it does

A bash script that checks a folder for any files updated in the last 24 hours and backs them up automatically into a compressed `.tar.gz` file. It runs every day at midnight using a cron job.

## How to run it

```bash
chmod +x backup.sh
./backup.sh /path/to/source /path/to/destination
```

## What I learned

- Writing bash scripts
- Working with files and directories in Linux
- Using loops and conditionals in shell scripting
- Scheduling automated tasks with cron

## Course

IBM Linux Commands and Shell Scripting — Coursera
