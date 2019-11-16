##  As a DevOps Engineer I want to set up Configuration Management System using Ansible. I have Two Target Machine and One Ansible Control node. 
### I want to setup SSH between Ansible Control node with that of Target Node


![Set UP ](https://github.com/NarendranathPanda/learning_ssh/blob/master/setup-ssh/set-up.PNG)


1. Generate your keys (Ansible Control Node // It wants to access target)
1. Create a file "authorized_keys"   at the root user's .ssh directory . 
   1. Change the .ssh directory mode to 700(executable) and authorized_keys file mode 600(read & write)
1. Add the Ansible public key to the   "authorized_keys" of the Target Node
1. Optional (restrict the password authentication )
