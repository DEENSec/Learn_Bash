# Learn_Bash
This page contains Bash scripting notes. Newbies can use these notes to improve their Bash scripting knowledge. Everything is structured to be easy to understand.
![image alt](https://github.com/DEENSec/Learn_Bash/blob/main/Bash_script.png?raw=true)



## __Bash Scripting Starter__

### What is this?
Every Bash script must start with a shebang (#!) line to tell the system which interpreter to use.

### Basic Format

#!/bin/bash
This line tells your system to use the Bash shell (located at /bin/bash) to run the script.

### Explanation


| Part        | Meaning                                                |
| ----------- | ------------------------------------------------------ |
| `#!`        | Called the **shebang**                                 |
| `/bin/bash` | Path to the **Bash interpreter** on most Linux systems |



### Try It Yourself


#### 01 open a terminal.

#### 02 Create a script

   nano hello.sh

#### 03 Add

#!/bin/bash
echo "Hello, world!"

#### 04 Save and exit (Ctrl+X, then Y, then Enter).

#### 05 Make it executable

chmod +x hello.sh

#### 06 Run it

## Tip

Use #!/usr/bin/env bash if you're writing scripts that need to be portable across different systems (e.g., not all have /bin/bash).

#!/usr/bin/env bash


