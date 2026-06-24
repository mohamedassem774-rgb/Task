commands

---------------------------------------
ansible-navigator run tasks_adv.yml -m stdout  --syntax-check
playbook: /root/tasks.yml
----------------------------------------
ansible-navigator run tasks_basic.yml -m stdout  --syntax-check
playbook: /root/tasks.yml
-----------------------------------------
ansible-navigator doc cisco.ios.facts

 ansible-navigator doc cisco.ios.banner
 
 ansible-navigator doc cisco.ios.user
 
 ansible-navigator doc cisco.ios.config
 
 ansible-navigator doc ios_interfaces
 
 ansible-navigator doc cisco.ios.command
 
 ansible-navigator doc cisco.ios.hostname

----------------------------------------
ansible-navigator run tasks_basic.yml -m stdout 
ansible-navigator run tasks_adv.yml -m stdout
