This is yml file to install apache2 on Ubuntu 14.04 with ansible.
Edit host.txt: provide IP of Target machine.
run command: 
ansible-playbook -i host.txt apache.yml -u username -s -k
