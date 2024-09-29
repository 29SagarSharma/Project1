How to run the script
Provide the path of script. If we are at same directory in which our script present so we can use the below command to run it.
Usage: ./script.sh [options] 

1.Features:list_processes
  Usage: ./script.sh list_processes
  Working: Feature to display all currently running processes, including their PID, owner, and memory usage.     
 
2.Feature:kill_process
  Usage: ./script.sh kill_process <PID>
  Working: Feature to kill a process by entering its PID.

3.Feature:monitor_system
  Usage: ./script.sh monitor_system
  Working: Feature to monitor and display the system load and CPU usage in real-time.

4.Feature:disk_usage
  Usage: ./script.sh disk_usage
  Working: Feature provide an option to display the disk usage of all mounted filesystems.

5.Feature:available_diskspace
  Usage: available_diskspace
  Working: Feature to view available disk space on all mounted filesystems.

6.Feature:list_diskpartition
  Usage: ./script.sh list_diskpartition
  Working: Feature to list all disk partitions and their statuses.

7.Feature:search_files
  Usage: ./script.sh search_files <directoryname> <filename>
  Working: Feature that allows searching for files by name in a specified directory.

For creating ,deleting and to change the password you need the root or administration access of your system.
8.Feature:create_item
  Usage: ./script.sh create_item <path> <file|directory>
  Working: Feature to create a file in a specified directory

9.Feature:delete_item
  Usage: ./script.sh delete_item <path> 
  Working: Feature to delete a file/directory by providing its path

10.Feature:rename_item
  Usage: ./script.sh rename_item <old_path> <new_path>
  Working: Feature to rename a file/directory

11.Feature:backup_item
  Usage: ./script.sh backup_item <source_path> <backup_path>
  Working: Feature to create a backup of a specified file or directory to a designated location.

12.Feature:list_user
  Usage: ./script.sh list_user
  Working: Featuire to list all users on the system along with their UID and home directory.

13.Feature:add_user
  Usage: ./script.sh add_user <username> <home_dir>"
  Working: Feature to add a new user to the system with the ability to specify the username and home directory.

14.Feature:delete_user
  Usage: ./script.sh delete_user <username>
  Working: Feature to delete an existing user from the system.

15.Feature:change_password
  Usage: ./script.sh change_password <username>
  Working: Feature to change the password of a specified user

16.Feature:system_uptime
  Usage: ./script.sh system_uptime
  Working: Feature to display how long the system has been running.

17.Feature:show_memory_usage
  Usage: ./script.sh show_memory_usage
  Working: Feature to show current memory usage, including total, used, and free memory.

18.Feature:help
  Usage: ./script.sh --help
  Working: Feature that displays information on how to use the different features of the script.
