#
# update-hosts
#
# This script download different hosts files containing domains of sites with advertising, viruses and malwares.
# It compose the new final hosts file using address found in /hosts.local making a backupd of the previous
#
#
Instructions:

- Clone the git
  git clone https://github.com/AlphaSocket/update-hosts
  
- Move in the dir 
  cd update-hosts
  
- Run update-host as Root
  sudo ./update-host
