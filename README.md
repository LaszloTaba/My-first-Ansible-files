# My first Ansible files
My first Ansible files

These are the first Ansible files I uploaded to GitHub. I wanted to show that I understand the basics of how Ansible works. The repository includes a main file, configure-vm.yml, which is a playbook that runs a yum update and installs apache, ftp, and virtualization host packages on servers included as "new-machine" hosts. The playbook also configures firewalls for those packages.

The other files here -- install_apache.yml, install_ftp.yml, install_virtualization_host.yml, main.yml, restart_firewall.yml, run-configure-vm.yml, yum_update.yml -- are part of the role I wrote based on the configure-vm.yml playbook. After running the ansible-galaxy command to create a file structure for this role, copy run-configure-vm.yml into your /etc/ansible directory, and then copy the rest of the files into the role's task directory.
