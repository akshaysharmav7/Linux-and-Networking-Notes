- `whoami` — displays  username
- `pwd` — prints working directory
- `cat` — displays file content
- `ls` — List directory
- `sudo -i` — To switch to root user
- `exit` or `logout`  — To exit or logout from the root/user
- `cd` or `cd ~` — move to home directory
- `cd /`  — move to root directory
- `cd ..`   — move to previous directory
- `uptime`  — shows system uptime
- `cp file.ext dir/` - copy file from one directory to another
- `cp -r dirname dirname` - copy directory to directory
- `clear` - clears the terminal
- `touch file.ext` - To create a new file
- `mkdir dir` - create a new directory
- `rm filename` - remove file
- `rmdir` - remove directories
- `rm -rf dir` - force remove directories with file
- `rm -r * dir` - remove everything in the current directory with force
- `mv file/folder dir/`  - move directories/files

Vimbar Text Editor Commands:

Three modes: Command, Insert, Extended Command
:      -    pressing this takes you to the extended command mode

:w   - Write and save the changes

:q   - Save and quit from the vim editor

:q!  - Quit the editor without saving

Esc -    Escape takes you to the command mode

I      -     Pressing ‘I’ button takes you to the Insert Mode

Networking Commands:

- `ip addr show` - To check ip address
- `traceroute [ip/hostname]` - To trace the path of the network packet
- `ping [ip/hostname]` - To check connectivity to the network
- `netstat/ss -antp` - To check port related details
    
    **- `ss -antp`**
    
    - `a` → all TCP sockets (LISTEN + ESTABLISHED + others)
    - `n` → numeric addresses
    - `t` → TCP only
    - `p` → show process info
        
        **What you see:**
        
        - All **TCP connections**, both **listening and established**, with their associated processes.
    
    **-  `ss -tunlp`**
    
    - `t` → TCP
    - `u` → UDP (so both TCP + UDP)
    - `n` → numeric addresses
    - `l` → **only listening sockets**
    - `p` → show process info
    
    **What you see:**
    
    - All **listening TCP and UDP sockets**, along with the **process using them**.
    - Won’t show **established connections**, only ports that are waiting for connections or UDP listeners.
- `dig/nsloolup [hostname]` - query DNS (Domain Name System) servers and get information about domain names and IP addresses.
- `ip route / route -n` -  show or manage the system’s routing table — `ip route` is the newer and preferred tool.
- `mtr [hostname/ip]` -  show live information about the data packets hopping to that route
- `telnet [hostname/ip]` -  Test connectivity to remote servers and ports, and for troubleshooting network services

Theres a tool named nmap that can scan different network details but its should be used carefully as it is illegal in many countries