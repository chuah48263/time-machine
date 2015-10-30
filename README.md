# time-machine

"time-machine" is a bash command which helps you to assign a backup name to every revision of your Time Machine backups.

When you want to review your files and folder in Time Machine, it eases you by assigning a static name to your backup, so that you won't need to remember the time you made changes to your OS X.

"time-machine" works by creating a hidden text file named ".Time_Machine.txt" with transparent icon on your desktop, whenever you create a new backup with a backup name using this tool, it will assign that name into "~/Desktop/.Time_Machine.txt".

When you use Time Machine to review old files and folders, just navigate to your "Desktop" folder in your Finder's sidebar, click on ".Time_Machine.txt", then press space bar on your keyboard to view your backup name. You might need to have "AppleShowAllFiles" toggled on for this tool to work best.

# Installation

Install by issuing the following command in your teminal:
```
git clone https://github.com/chuah48263/time-machine.git ~/.time-machine/ && cd ~/.time-machine/ && chmod +x time-machine && ./time-machine`
```

# Usage

### time-machine \<usage>
- backup [-b] - Backup using Time Machine after creating a new backup name."
- create [-c] - Create a new backup name."
- delete [-d] - Revert to last backup name without stopping ongoing TM."
- doctor [-m] - Check for problem(s) of "time-machine" if any."
- final [-f] - List latest backup name."
- help [-h] - Manual page for "time-machine"."
- init [-i] - Initialization / Reinstallation / Repairation of "time-machine"."
- list [-l] - List all previous backup name."
- now [-n] - Backup using Time Machine without creating a new backup name."
- revert [-r] - Revert to last backup name and stop ongoing TM if running."
- status [-s] - Check the backup status of Time Machine."
- terminate [-t] - Terminate ongoing Time Machine backup."

### Reminder
- If you create a new backup name while Time Machine has already started running, Your new backup name will not be registered into the ongoing backup."
