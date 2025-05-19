# DSpace-7.6_playbook
This repository contains the ansible playbooks for installing DSpace v7.6 on a linux server
<a href="https://docs.ansible.com/ansible/latest/getting_started/index.html" target="_blank">Official Ansible documentation</a>


Prerequisites
Before running the playbooks, ensure you have the following:

Ansible Installed:

Install Ansible on your control machine:</br>
<code>sudo apt update
sudo apt install ansible -y
</code>

Access to Target Machine:

Ensure SSH access to the target machine(s).
Update the inventory.ini file with the correct target machine details.
Dependencies:

Python and essential build tools should be pre-installed on the target machine.

The inventory.ini file specifies the target host(s) for deployment. Update it as needed:</br>
<code>[hosts]
your_target_machine ansible_user=your_user
</code>

# _Running the playbook_

<code>ansible-playbook -i inventory.ini [playbook]
</code>


