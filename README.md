# Daily work log

Simple script to generate md log files.

During the day, I run 'daily_work_log' when I finish a task.

The script will create an md file in the application's directory if one does not already exist for the current week.

If a log file does exist, it will read it and look for a header with today's date.  If a header with today's date does not exist, it will append one.

Lastly, it will open the file using a configurable editor command.
