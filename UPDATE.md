= Steps for firmware update saving configuration from previos version =
- add remote https://github.com/MarlinFirmware/Marlin as upstream
- create new branch from current (for backup purpose)
- checkout desired branch from upstream
- rebase current branch onto desired upstream branch
- merge conflicts (should be only configuration)
- commit
- push