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
mkdir practice
cd practice
touch notes.txt
