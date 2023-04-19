# repave
Situation

Messed up on the password from this command in vCenter:
  /usr/lib/vmware-wcp/decryptK8Pwd.py 
  Effectivly locked out of supervisor cluster

Repave the supervisor Cluster

Burger Menu -> Administration -> vCenter Server Extentions -> vSphere ESX Agent Manager -> configure -> ESX Agencies -> select sup vm -> delete agency
Watch in vCenter supervisor VM being delete and then re-build

