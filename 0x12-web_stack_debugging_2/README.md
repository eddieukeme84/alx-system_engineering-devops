# Web stack debugging #2

<p align="center">
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/287/99littlebugsinthecode-holberton.jpg" width="" hieght="" />
</p>

## General Requirement & Environment
<img src="https://github.com/TosinISOGUN/TosinISOGUN/blob/main/ALX.jpeg?raw=true" width="300" height="100" />

- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted on Ubuntu 14.04 LTS.
- All files should end with a new line.
- A `README.md` file, at the root of the folder of the project, is mandatory.
- All Bash script files must be executable.
- Bash scripts must pass `Shellcheck` without any error.
- The first line of all Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all your Bash scripts should be a comment explaining what is the script doing.


This was the third in a series of web stack debugging projects. In these
projects, I was given broken/bugged webstacks in isolated containers,
and tasked with fixing the web stack to a working state. For each
task, I wrote a script automating the commands necessary to fix the
web stack.

## Tasks :page_with_curl:

* **0. Run software as another user**
  * [0-iamsomeonelese](./0-iamsomeonelese): Bash script that runs the command
  `whoami` under the user passed as argument.
  * Usage: `./0-iamsomeonelese <user>`

* **1. Run Nginx as Nginx**
  * [1-run_nginx_as_nginx](./1-run_nginx_as_nginx): Bash script that fixes a
  web server to run Nginx listening on port `8080` as the `nginx` user.

* **2. 7 lines or less**
  * [100-fix_in_7_lines_or_less](./100-fix_in_7_lines_or_less): Bash script
  that fixes a web server to run Nginx listening on port `8080` as the `nginx`
  user.
  * 7 lines long


## AUTHOR
  
By EMMANUEL UKEME
