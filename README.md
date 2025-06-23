# Bash Log Generator

##  Tasks Performed

- Created and ran a Bash script (`script.sh`) that:
  - Creates a `logs/` directory
  - Generates 3 log files: `app.log`, `system.log`, `auth.log`
  - Writes 50 fake log entries using random IPs, users, and log levels

##  Commands Used

- **To find all usernames in logs:**
  ```bash
  grep -o 'User=[^ ]*' logs/*.log | cut -d= -f2 | sort | uniq

grep "ERROR" logs/*.log


## 🟢 Beginner Bash Tasks

- **Print Your Name:**  
  Created a script that stores a name in a variable and prints a greeting message.
  ```bash
  # hello.sh
  my_name="Sufyan"
  echo "Hello, $my_name!"


🟡 Intermediate Level
 -mkdir practice
 -cd practice
 -touch notes.txt

Section 1: Terminal Basics & File Management
1. Navigate to your home directory, then list all hidden files. Which ones are commonly used for configuration?
#
-cd ~
-ls -a

2. Create a directory named projects, then create a file called README.md inside it with the text “My Projects”.
#
mkdir projects
echo "My Projects" > projects/README.md

3. Change the permissions of a file script.sh to make it executable only by the owner.
chmod 700 script.sh

4. Copy all .txt files from the current directory into a folder named backup. If it doesn’t exist, create it.
#
mkdir -p backup
cp *.txt backup/

5. One-liner that finds all .log files under /var/log and outputs their filenames and sizes.
#
find /var/log -type f -name "*.log" -exec du -h {} +

