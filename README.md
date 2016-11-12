# update-hosts
This script download different lists from the web containing domains of sites with advertising, viruses and malwares.

It make a backup of the /etc/hosts file and compose the final hosts file using previous file and a file found at  /etc/hosts.local containing custom entry for local pc like virtualhosts redirects.
During the first run the original /etc/hosts file is renamed as /etc/hosts.local

### Prerequisites

Bash shell 

## Getting Started
- Clone the git
```
git clone https://github.com/AlphaSocket/update-hosts
```  

### Run
- Run update-host as Root
```
  sudo ./update-hosts/update-hosts
```
