# Edugrade, Linux Devops Eng, Python project 1 - By Ray de Groat

A mini project assignment for the Python moduel at Edugrade's Linux DevOps Engineering course. Instructions for the assignment follows.

Mini project 1- Python programming

Specification:
Write a script named loganalyzer.py. The script is used as follows:

python loganalyzer.py filepath action

where filepath is the path to the log file to analyze and action is the action required by the script.

Valid values for the action are statistics, error, notice. The action determines what the script outputs.

statistics – Prints the statistics as follows:

errors 340
notice 450

where the first value is the type of log entry and the second value is the number of such entries there are in the file.

error – Prints the errors in the file with each row as follows: date message

notice - Prints the notice in the file with each row as follows: date message

The script reads a logfile in the format seen in the provided sample file test.log. Use that file to evaluate your script. At the first line of the script enter a comment with the following format:

# your_name your_student_email

Deliverables
The script should be submitted to the designated mini project 1 on the portal.
