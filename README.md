Role Name
=========

Galera Role.  

Install Galera, Configure and Secure.

Requirements
------------

Predifined account for ansible with sudo provileges.

Role Variables
--------------

Edit in *deploy.yml*

`galera_cluster_name:`  
`galera_cluster_members: [ SERVER1, SERVER2, SERVER3, ]`  

Add your server in inventory file.  
Use `galera_bootstrap=1` for the first Server which will initiate cluster creation  
 
Edit *galera/default/main.yml* whith your own values  

Dependencies
------------

N/A

License
-------

BSD

Author Information
------------------

