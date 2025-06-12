# 🔰Learn_Bash🔰
This page contains Bash scripting notes. Newbies can use these notes to improve their Bash scripting knowledge. Everything is structured to be easy to understand.
![image alt](https://github.com/DEENSec/Learn_Bash/blob/main/Bash_script.png?raw=true)



## 01. Bash Scripting Starter

### What is this?
Every Bash script must start with a shebang (#!) line to tell the system which interpreter to use.

### 🔹Basic Format

#!/bin/bash
This line tells your system to use the Bash shell (located at /bin/bash) to run the script.

### 🔹Explanation


| Part        | Meaning                                                |
| ----------- | ------------------------------------------------------ |
| `#!`        | Called the **shebang**                                 |
| `/bin/bash` | Path to the **Bash interpreter** on most Linux systems |



### 🔹Try It Yourself


🟢 step 01: open a terminal.

🟢 Step 02: Create a script.

          nano hello.sh

🟢 Step 03: Add this code inside the file

         #!/bin/bash
         echo "Hello, world!"

🟢 step 04: Save and exit (Ctrl+X, then Y, then Enter).

🟢 step 05: Make it executable

        chmod +x hello.sh

🟢 step 06: Run it

        ./hello.sh

#### 🔴Output

    Hello, world!

### 🔹Tip

Use #!/usr/bin/env bash if you're writing scripts that need to be portable across different systems (e.g., not all have /bin/bash).

#!/usr/bin/env bash
