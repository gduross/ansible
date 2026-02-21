Useful Commands
----------------------------------------------
ansible-playbook ansible_pb_juniper_backup_config.yml -i /etc/ansible/inventory01.yml
ansible-playbook ansible_pb_juniper_vmx_show_version_int.yml -i /etc/ansible/inventory04.yml -l juniper_devices2 


Useful Links
----------------------------------------------
# https://www.juniper.net/documentation/us/en/software/junos-ansible/ansible/topics/concept/junos-ansible-modules-overview.html

Note:
----------------------------------------------
When making changes from Ansible, the playbook status may be successful, but if no change (already made) on the Juniper config, the commit history will not show a change.


Log:
----------------------------------------------
2/21/2026 - All playbooks in Juniper folder updated and or validated. Obsolete playbooks removed.
