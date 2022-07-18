# Ansible
## Prerequisites:
*  Install Ansible
*  Uncomment the below line in file `/etc/ansible/ansible.cfg`
     ```shell script
      host_key_checking = False
      ```
## Ansible useful commands
* To check connectivity
   ```shell script
    ansible smarthome -i hosts -m ping
   ```
