Useful Commands
----------------------------------------------
ansible-playbook ansible_pb_juniper_backup_config.yml -i /etc/ansible/inventory01.yml


Useful Links
----------------------------------------------
# https://www.juniper.net/documentation/us/en/software/junos-ansible/ansible/topics/concept/junos-ansible-modules-overview.html

Note:
----------------------------------------------
When making changes from Ansible, the playbook status may be successful, but if no change (already made) on the Juniper config, the commit history will not show a change.

