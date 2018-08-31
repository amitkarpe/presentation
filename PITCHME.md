# Ansible AWX

SOLVE IT. AUTOMATE IT. SHARE IT.
#![Ansible](https://upload.wikimedia.org/wikipedia/commons/2/24/Ansible_logo.svg)
---

```bash
#!/bin/bash
# https://github.com/amitkarpe/scripts/invitations
yum install vim tmux nano unzip wget git net-tools bind-utils yum-utils iptables-services bridge-utils bash-completion kexec-tools sos psacct docker ansible php php-pear --assumeyes
echo "echo ''" >> ~/.bash_profile
echo "uptime" >> ~/.bash_profile
```

---?gist=amitkarpe/42c2d7b97b1abafd87eac6f3d98bad9b&lang=Bash&title=GIST:Bash
@[1-2](Set the host name and IP address)
@[3-3](Teardown the cluster)
@[4-5](Provision the cluster with single node)
---
```
package main
import "fmt"
func main() {
    fmt.Println("Hello, world!")
}
```
@[1]
@[3]
@[5-7]
---
```
from time import localtime

activities = {8: 'Sleeping', 9: 'Commuting', 17: 'Working',
              18: 'Commuting', 20: 'Eating', 22: 'Resting' }

time_now = localtime()
hour = time_now.tm_hour

for activity_time in sorted(activities.keys()):
    if hour < activity_time:
        print activities[activity_time]
        break
else:
    print 'Unknown, AFK or sleeping!'
```
---
### Sample Code
- Linux
- Install nginx
- RedHat Vs Debian
