# repave
Situation

Messed up on the password from this command in vCenter:
  /usr/lib/vmware-wcp/decryptK8Pwd.py 
  Effectivly locked out of supervisor cluster

Repave the supervisor Cluster

Burger Menu -> Administration -> vCenter Server Extentions -> vSphere ESX Agent Manager -> configure -> ESX Agencies -> select sup vm -> delete agency
Watch in vCenter supervisor VM being delete and then re-build
Repeate for the other 2 supervisor VM's (when selecting the supervisor VM the ESX Agency name shows up in the Notes section) 


