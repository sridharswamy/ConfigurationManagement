# ConfigurationManagement

###How to run
1. Create two servers:
    * A master server that runs Ansible.    
    * A new node that will be serving as our web server.
(For instructions regarding steps 1 & 2, you can refer https://github.com/CSC-510/Course/blob/master/Materials/CM.md)    

2. Vagrant only allows one virtual machine configuration per directory. We create two separate directories called node0 and node1, and then run the commands in there.    

3. Start the two servers by using the `sudo vagrant ssh` command in separate terminals.   

4. Copy the file `playbook.yml` into the master server.    

5. Run the ansible playbook file using the command `sudo ansible-playbook -i inventory playbook.yml`.    
    
###Screencast    
[YouTube link](https://youtu.be/AeqfMdMg0OY)    
